# Overview
TechPay needs to get the actual Usage value in order to generate invoice for billing purposes. Hence, TechPay needs to call each indivual `Products`' usage API endpoints to get the daily/monthly usage for a particular `Project` and a particular `Item`. 
P.S. Check out [Domain Terms](domain_terms.md) for more information about domain information.

## Requirements
### Functional Requirements
* Accepts a valid `Item` identifier.
* Accepts a valid `Project` identifier.
* Accepts a date range.
* Returns usage data based on the above parameters.

### Security Requirements
* Usage API endpoint exposes only to TechPay.
* Usage API endpoint has to be authenticated.
* Usage API endpoint exposes to TechPay IP/network.

## Key Concepts
The key concept would be the authentication flow. We are using Azure Active Directory (AAD) for authentication. We are following Access Token way of authentication where TechPay calls AAD and get access token before calling Usage API. The Usage API will then validate if the request is valid.

## Workflow
```mermaid
sequenceDiagram
TechPay->>TechPass AAD: 1 Register Usage API App
TechPay->>TechPass AAD: 1.1 Upload Public Certificate
TechPay->>TechPass AAD: 1.2 Create App Role (Usage.Read)
TechPay->>TechPass AAD: 1.3 Add API Permision
Note right of TechPay: Establish client credential flow
TechPay->>TechPay: 2.1 Form Assertion (JWT)
TechPay->>TechPay: 2.2 Sign by Private key
TechPay->>TechPass AAD: 2.3 Using this Assertion and request for JWT Access Token
TechPass AAD-->> TechPay: 3. Return a JWT Access Token
TechPay->>Product: 4. Pass JWT Access Token through API Header
Product->>Product: 5.1 Decoding JWT Access Token
Product->>TechPass AAD: 5.2 Call JWKS to get public signing keys
TechPass AAD-->>Product: 6 Return the list of rotated keys
Product->>Product: 7 Validate all necessary data*
Product-->>TechPay: 8. Return Usage Data API Response
```
### *: Validate all neccessary data:
1. Audience (App Id URI) matches
2. App ID matches
3. Issuer matches
4. Tenant matches
5. x5t & kid matches JWKS keys
6. Not expired and within valid time window (exp, nbf)

# Getting Started
There's a demo [repository](https://bitbucket.ship.gov.sg/projects/TECHSBUSIN/repos/techpay-demo-usage-api) that you can check. It includes the workflow from step 2 to 8. There's a sample app registered as well (Step 1). It can be used as a reference for both the API contract and the workflow implementations.