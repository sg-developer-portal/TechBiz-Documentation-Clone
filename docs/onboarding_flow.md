# New Case

1. Agency will follow the TechBiz onboarding flow, once the agency's project is approved, a TechBiz Project ID will be issued
2. Agency will fill up the Product Configuration form
3. TechBiz will inform Product (API) about the configuration and the TechBiz Project ID
4. During operation, Usage API will use this TechBiz Project ID as the unique identifier

# Existing Case

First time migration TechBiz will do the mapping.

## Onboarding&migration steps

1. Onboarding (TechBiz/Damien will help)
   1. Product
   2. Items (Usage Api)
   3. Plans
2. Migration (TechBiz/Damien help)
   1. Projects
   2. Subscriptions

## Usage API Integration steps

1. Test the API manually (By TechBiz)
   1. Connectivity (Setup in TechPass, client credentials flow)
   2. Different itemKey and project (Product's side key)
   3. Different time range, from and to
   4. Response format
      1. Optional: Passing the metatdata
2. Setup all the above steps (staging first)
3. Issuing projectID (Product need to accept this as a foreign key)
4. Test the new projectID
