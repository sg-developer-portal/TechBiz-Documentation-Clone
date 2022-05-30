# Create system

**Prerequisites:**

-   Public officer with a valid organisation email (for example user_name@agency.gov.sg)

-   non-SE Government Standard Image Build (GSIB) device

**What is a system?**

A system is an agency namespace in TechBiz.

To subscribe to [Singapore Government Tech Stack (SGTS)](https://www.developer.tech.gov.sg/singapore-government-tech-stack/overview/index.html) products, agencies need to create a system in the TechBiz portal.

> **Note:** An agency can have multiple systems in TechBiz.

**Who can create a system?**

A public officer with a valid organisation email.

Topics:

-   **Request to create a system**
-   **Approve or reject system creation request**
-   **Configure products**

## Request to create a system

> **Note:** By default, the public officer who requests to create a system is assigned the primary subscription admin role for that system in TechBiz.

**To submit a system creation request:**

1.  Log in to the [TechBiz portal.](http://portal.dev.techbiz.suite.gov.sg/)

> **Notes:**
>
> - If you log in with OTP, you are assigned the **OTP** role.
>
> - If you log in with [TechPass,](https://www.developer.tech.gov.sg/products/categories/digital-identity/techpass/overview.html) you are assigned the **USER** role.

2.  In the **Overview** page, click **View systems**.

> **Note:** Alternatively, from the **sidebar,** click **Systems.**

3.  In the **Systems** page, click **Create system.**

![Display Create system](/images/create_system.png)

4.  Ensure that you have the required information ready and click **Next.**

5.  Select the checkbox to agree to the terms and conditions mentioned in the **SGTS Universal Service Terms** and click **Next.**
    
> **Note:** Read and select the checkbox to proceed further to the next step. To download the agreement, click **Download the SGTS agreement** link.

![Display Create system](/images/create_system_UST.png)

6.  Specify the required **System details** and click **Next.**

!> **Important:** Unless mentioned otherwise, all fields are mandatory.

| **Field Name** | **Description** |
|---- |---- |
| **Account details** | This section is for agencies to specify their account details|
| **Agency name** | Select your agency name from the drop-down list. <ul><li>If your agency is [GovTech]((https://www.tech.gov.sg/) you need to enter the **Agency department,** **Cost center,** and **Fund center** in the billing details section.</li> <li>For other government agencies, enter your **Sub Business Unit (SBU)** details.</li></ul>|
| **System name** | Enter your system name.|
| **System ID** | The system id is automatically generated and cannot be edited. *(Definition and purpose. TBC.)* |
| **Digital Governance Platform (DGP) ID** | Depending on whether your agency has a DGP ID or not; select **Yes, I have a DGP ID** or **No, I do no have a DGD ID.** If yes select your **DGP System ID** from the dropdown. The **sub system description** appears.  <ul><li>If your agency has multiple DGP IDs, you can select multiple **DGP System IDs** from the dropdown.</li> <li>If you are unable to locate your DGP ID, click **No, I do not have a DGP ID,** and update accordingly in due course.</li></ul>
| **Subscription admins**| This section is meant for public officers with a valid organisation email. Enter the details of the primary and secondary subscription admins. <ul><li>If the primary and secondary subscription admins do not have a TechPass account, these will be created automatically after the system creation request is approved.</li></ul>
| **Primary subscription admin** | By default, the requestor is assigned as the primary subscription admin. Hence, this section displays details of the requestor. <ul><li> The primary subscription admin can only be a public officer with a valid organisation email.</li></ul>
| **Email address** | By default this displays the organisation email address of the requestor. <ul><li>If the requestor’s email address is linked to a TechPass account, the First name, Last name and Contact number are displayed automatically and cannot be edited; otherwise requires the requestor’s input.</li></ul>
| **First name** | Enter the first name of the requestor. |
| **Last name** | Enter the last name of the requestor. 
| **Contact number** | Enter the contact number of the requestor.
| **Secondary subscription admin** | This section displays details of the secondary subscription admin. <ul><li>Secondary subscription admin can only be a public officer with a valid organisation email.</li></ul>
| **Email address** | Enter the email address of the secondary subscription admin. <ul><li>Must be a public officer with a valid organisation email.</li><li>If the secondary subscription admin email address is linked to a TechPass account, the **First name,** **Last name,** and **Contact number** are displayed automatically and cannot be edited; otherwise requires the requestor’s input.</li></ul>
| **First name** | Enter the first name of the secondary subscription admin. |
| **Last name** | Enter the last name of the secondary subscription admin. 
| **Contact number** | Enter the contact number of the secondary subscription admin.
| **Technical admin** | This section displays details of the technical admin. <ul><li>The technical admin can be a public officer or a vendor with a valid organisation email.</li></ul>
| **Email address** | Enter the email address of the technical admin. <ul><li>If the technical admin is a public officer, then the organisation field cannot be edited. (To check if it is displayed automatically)</li> <li>If the technical admin email address is linked to a TechPass account, the **First name,** **Last name,** and **Contact number** are automatically displayed and cannot be edited; otherwise requires requestor’s input.</li></ul>
| **First name** | Enter the first name of the technical admin. |
| **Last name** | Enter the last name of the technical admin. 
| **Contact number** | Enter the contact number of the technical admin.
| **Organisation** | Enter the organisation name of the technical admin.
| **Billing details** | This section displays details of the billing admin. <ul><li>The billing admin can only be a public officer with a valid organisation email.</li></ul>
| **Email address** | Enter the email address of the billing admin. <ul><li>If the billing admin email address is linked to a TechPass account, the **First name,** **Last name,** and **Contact number** are automatically displayed and cannot be edited; otherwise requires requestor’s input. </li></ul>
| **First name** | Enter the first name of the billing admin. |
| **Last name** | Enter the last name of the billing admin. 
| **Contact number** | Enter the contact number of the billing admin.
| | **Notes:**<ul><li>If your agency is GovTech, you need to fill in the **Agency department,** **Cost center,** and **Fund center** details.</li><li>All other agencies need to fill in the SBU details.</li></ul>
| **Agency department** | Enter the department name.
| **Cost center** | Enter the cost center code for your agency. This code will be used by the Finance for internal GovTech inter-department charging/journal entry.
| **Fund center** | Enter the fund center details. 
| **SBU** | Enter the sub business unit. 

![Display account details](/images/acct_det.png)

![Display subscription admin](/images/subscr_admin.png)

> **Notes:**
>
> - To save your entries, click **Save draft.**
>
> - To resume editing, locate your system in the **Systems page** and click **Edit Draft.** To proceed further to the next step, click **Next.**

7.  Select the required **products** and click **Next.**

8.  Select the required product **plan(s)** and click **Next.**

| **Field name** | **Description**
|---- |---- 
| **Select plan(s)** | This section is for agencies to select product subscription plan(s). <ul><li>To select a subscription plan, go to the individual product tab. You need to select subscription plan(s) for all the required product(s) before you can proceed to the next step.</li></ul>
| **Select subscription period**| Select **Start date.** This is the date when your agency intends to start using the SGTS products that they have subscribed to. <ul><li>Actual start date will be later than the selected start date as it includes the time required for:</li>
<li>1. The agency approver to approve the system creation request.</li>
<li>2. The agency to provide product configuration details.</li>
<li>3. The product team to provision the resources.</li>
| **Product agreement** | To download a copy of the product’s terms and conditions, click **Product agreement.**
| Select a plan| This refers to the subscription plan which contains details of the chargeable items in a product with the specified charges. The plans are:<ul><li>**Bundled plan-** To subscribe to multiple items in a product.</li><li>**Individual plan-** To subscribe to a single item in a product.</li><li>**Add-ons-** To subscribe to a single item in a product. However, cannot be selected on its own and must be included with an individual plan or a bundled plan.


9.  Specify the approver details and click Next.

!> **Important:** Unless mentioned otherwise, all fields are mandatory.

| **Field name** | **Description**
|---- |---- 
| **Approver name** | Enter the full name of the approver. 
| **Approver email** | Enter the email address of the approver. <ul><li>Approver can only be a public officer with a valid organisation email.</li></ul>
| **Designation** | Enter the designation of the approver. <ul><li>Approver can only be a Deputy Director and above.</li></ul>
| **Upload documents** | Click Choose a file to upload supporting documents. For example, approval email and AOR. <ul><li>You can upload files up to 10MB.</li><li>A maximum of 50 files per upload.</li><li>Supported file types: .jpg, .jpeg, .png, .pdf, .zip, .msg</li><li>Supported characters in upload file names: alphanumeric, space, hyphen, underscore, period.</li></ul>
| **Remarks to approver** | This field is optional. However, it is recommended to specify your reasons for seeking approval. For example, requesting approval to subscribe to SHIP-HATS for Project X.

10. Make sure the information displayed on this page is correct and
click **Submit.**

> **Notes:**

-   To edit your inputs, go to the required tab and click **Edit.**

-   To download a summary of the form, click **Download summary.**

11. In the **Submit for approval** pop-up window, review the terms
and conditions, select all **checkboxes** and click **Submit.**

\<submit1.png\>

\<submit2.png\>

## Approve or reject a system creation request

## Configure products

**Next steps:**

Invite users
