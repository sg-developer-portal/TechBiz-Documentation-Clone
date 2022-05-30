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
| **Digital Governance Platform (DGP) ID** | Depending on whether your agency has a DGP ID or not; select **Yes, I have a DGP ID** or **No, I do no have a DGD ID.** If yes select your **DGP System ID** from the dropdown. The **sub system description** appears.  
> **Notes:**
>
> - If your agency has multiple DGP IDs, you can select multiple **DGP System IDs** from the dropdown.
>
> - If you are unable to locate your DGP ID, click **No, I do not have a DGP ID,** and update accordingly in due course.
| ** Subscription admins**| This section is meant for public officers with a valid organisation email. Enter the details of the primary and secondary subscription admins.
> **Note:** If the primary and secondary subscription admins do not have a TechPass account, these will be created automatically after the system creation request is approved.


+----------------------
+-------------------------+--------------------------------------------+
| **Primary subscription  | By default, the requestor is assigned as   |
| admin**                 | the primary subscription admin. Hence,     |
|                         | this section displays details of the       |
|                         | requestor.                                 |
|                         |                                            |
|                         | Note: The primary subscription admin can   |
|                         | only be a public officer with a valid      |
|                         | organisation email.                        |
+-------------------------+--------------------------------------------+
| **Email address**       | By default, this displays the organisation |
|                         | email address of the requestor.\           |
|                         | \                                          |
|                         | Note: If the requestor's email address is  |
|                         | linked to a TechPass account, the **First  |
|                         | name, Last name** and **Contact number**   |
|                         | are displayed automatically and cannot be  |
|                         | edited; otherwise requires the requestor's |
|                         | input.                                     |
+-------------------------+--------------------------------------------+
| **First name**          | Enter the first name of the requestor.     |
+-------------------------+--------------------------------------------+
| **Last name**           | Enter the last name of the requestor.      |
+-------------------------+--------------------------------------------+
| **Contact number**      | Enter the contact number of the requestor. |
+-------------------------+--------------------------------------------+
| **Secondary             | This section displays details of the       |
| subscription admin**    | secondary subscription admin.              |
|                         |                                            |
|                         | Note: Secondary subscription admin can     |
|                         | only be a public officer with a valid      |
|                         | organisation email.                        |
+-------------------------+--------------------------------------------+
| **Email address**       | Enter the email address of the secondary   |
|                         | subscription admin.                        |
|                         |                                            |
|                         | Notes:                                     |
|                         |                                            |
|                         | -   Must be a public officer with a valid  |
|                         |     organisation email.                    |
|                         |                                            |
|                         | -   If the secondary subscription admin    |
|                         |     email address is linked to a TechPass  |
|                         |     account, the **First name, Last name** |
|                         |     and **Contact number** are displayed   |
|                         |     automatically and cannot be edited;    |
|                         |     otherwise requires the requestor's     |
|                         |     input.                                 |
+-------------------------+--------------------------------------------+
| **First name**          | Enter the first name of the secondary      |
|                         | subscription admin.                        |
+-------------------------+--------------------------------------------+
| **Last name**           | Enter the last name of the secondary       |
|                         | subscription admin.                        |
+-------------------------+--------------------------------------------+
| **Contact number**      | Enter the contact number of the secondary  |
|                         | subscription admin.                        |
+-------------------------+--------------------------------------------+
| **Technical admin**     | This section displays details of the       |
|                         | technical admin.                           |
|                         |                                            |
|                         | Note: The technical admin can be a public  |
|                         | officer or a vendor with a valid           |
|                         | organisation email.                        |
+-------------------------+--------------------------------------------+
| **Email address**       | Enter the email address of the technical   |
|                         | admin.                                     |
|                         |                                            |
|                         | Notes:                                     |
|                         |                                            |
|                         | -   If the technical admin is a public     |
|                         |     officer, then the organisation field   |
|                         |     cannot be edited.\                     |
|                         |     *(To check if it is displayed          |
|                         |     automatically*)                        |
|                         |                                            |
|                         | -   If the technical admin email address   |
|                         |     is linked to a TechPass account, the   |
|                         |     **First name, Last name** and          |
|                         |     **Contact number** are automatically   |
|                         |     displayed and cannot be edited;        |
|                         |     otherwise requires requestor's input.  |
+-------------------------+--------------------------------------------+
| **First name**          | Enter the first name of the technical      |
|                         | admin.                                     |
+-------------------------+--------------------------------------------+
| **Last name**           | Enter the last name of the technical       |
|                         | admin.                                     |
+-------------------------+--------------------------------------------+
| **Contact number**      | Enter the contact number of the technical  |
|                         | admin.                                     |
+-------------------------+--------------------------------------------+
| **Organisation**        | Enter the organisation name of the         |
|                         | technical admin.                           |
+-------------------------+--------------------------------------------+
| **Billing details**     | This section displays details of the       |
|                         | billing admin.                             |
|                         |                                            |
|                         | Note: The billing admin can only be a      |
|                         | public officer with a valid organisation   |
|                         | email.                                     |
+-------------------------+--------------------------------------------+
| **Email address**       | Enter the email address of the billing     |
|                         | admin.                                     |
|                         |                                            |
|                         | Note: If the billing admin email address   |
|                         | is linked to a TechPass account, the       |
|                         | **First name, Last name** and **Contact    |
|                         | number** are automatically displayed and   |
|                         | cannot be edited; otherwise requires       |
|                         | requestor's input.                         |
+-------------------------+--------------------------------------------+
| **First name**          | Enter the first name of the billing admin. |
+-------------------------+--------------------------------------------+
| **Last name**           | Enter the last name of the billing admin.  |
+-------------------------+--------------------------------------------+
| **Contact number**      | Enter the contact number of the billing    |
|                         | admin.                                     |
+-------------------------+--------------------------------------------+
|                         | Notes:                                     |
|                         |                                            |
|                         | -   If your agency is GovTech, you need to |
|                         |     fill in the **Agency department, Cost  |
|                         |     center and Fund center** details.      |
|                         |                                            |
|                         | ```{=html}                                 |
|                         | <!-- -->                                   |
|                         | ```                                        |
|                         | -   All other agencies need to fill in the |
|                         |     **SBU** details.                       |
+-------------------------+--------------------------------------------+
| **Agency department**   | Enter the department name.                 |
+-------------------------+--------------------------------------------+
| **Cost center**         | Enter the cost center code for your        |
|                         | agency. This code will be used by the      |
|                         | Finance for internal GovTech               |
|                         | inter-department charging/journal entry.   |
+-------------------------+--------------------------------------------+
| **Fund center**         | Enter the fund center details.             |
+-------------------------+--------------------------------------------+
| **SBU**                 | Enter the sub business unit.               |
+-------------------------+--------------------------------------------+

![Display account details](/images/acct_det.png)

![Display subscription admin](/images/subscr_admin.png)

> **Notes:**
>
> - To save your entries, click **Save draft.**
>
> - To resume editing, locate your system in the **Systems page** and click **Edit Draft.** To proceed further to the next step, click **Next.**

7.  Select the required **products** and click **Next.**

8.  Select the required product **plan(s)** and click **Next.**

+--------------------------+--------------------------------------------+
|                          |                                            |
+==========================+============================================+
| **Field name**           | **Description**                            |
+--------------------------+--------------------------------------------+
| **Select plan(s)**       | This section is for agencies to select     |
|                          | product subscription plan(s).              |
|                          |                                            |
|                          | Note: To select a subscription plan, go to |
|                          | the individual product tab. You need to    |
|                          | select subscription plan(s) for all the    |
|                          | required product(s) before you can proceed |
|                          | to the next step.                          |
+--------------------------+--------------------------------------------+
| **Select subscription    | Select **Start date.** This is the date    |
| period**                 | when your agency intends to start using    |
|                          | the SGTS products that they have           |
|                          | subscribed to.                             |
|                          |                                            |
|                          | Note:\                                     |
|                          | Actual start date will be later than the   |
|                          | selected start date as it includes the     |
|                          | time required for:\                        |
|                          | 1. The agency approver to approve the      |
|                          | system creation request.\                  |
|                          | 2. The agency to provide product           |
|                          | configuration details.\                    |
|                          | 3. The product team to provision the       |
|                          | resources.                                 |
+--------------------------+--------------------------------------------+
| **Product agreement**    | To download a copy of the product's terms  |
|                          | and conditions, click **Product            |
|                          | agreement.**                               |
+--------------------------+--------------------------------------------+
| **Select a plan**        | This refers to the subscription plan which |
|                          | contains details of the chargeable items   |
|                          | in a product with the specified charges.   |
|                          |                                            |
|                          |   ---------------------------------------  |
|                          |   **Plan type**    **When to use**         |
|                          |   ---------------- ----------------------  |
|                          |   **Bundled plan** To subscribe to         |
|                          |                    multiple items in a     |
|                          |                    product                 |
|                          |                                            |
|                          |   **Individual     To subscribe to a       |
|                          |   plan**           single item in a        |
|                          |                    product                 |
|                          |                                            |
|                          |   **Add-ons**      To subscribe to a       |
|                          |                    single item in a        |
|                          |                    product. However,       |
|                          |                    cannot be selected on   |
|                          |                    its own and must be     |
|                          |                    included with an        |
|                          |                    individual plan or a    |
|                          |                    bundled plan.           |
|                          |   ---------------------------------------  |
|                          |                                            |
|                          | *1. Types of pricing models -- fixed one   |
|                          | time, metered usage: TBC\                  |
|                          | 2. What happens if a chargeable            |
|                          | subscription plan is not available? What   |
|                          | are the options? TBC*                      |
+--------------------------+--------------------------------------------+



9.  Specify the approver details and click Next.

**Important:** Unless mentioned otherwise, all fields are mandatory.

+--------------------+-------------------------------------------------+
|                    |                                                 |
+====================+=================================================+
|                    |                                                 |
+--------------------+-------------------------------------------------+
| **Field Name**     | **Description**                                 |
+--------------------+-------------------------------------------------+
| **Approver name**  | Enter the full name of the approver.            |
+--------------------+-------------------------------------------------+
| **Approver email** | Enter the email address of the approver.\       |
|                    | Note: Approver can only be a public officer     |
|                    | with a valid organisation email.                |
+--------------------+-------------------------------------------------+
| **Designation**    | Enter the designation of the approver.\         |
|                    | Note: Approver can only be a Deputy Director    |
|                    | and above.                                      |
+--------------------+-------------------------------------------------+
| **Upload           | Click **Choose a file** to upload supporting    |
| documents**        | documents. For example, approval email and      |
|                    | AOR.\                                           |
|                    | Notes:                                          |
|                    |                                                 |
|                    | -   You can upload files up to 10MB.            |
|                    |                                                 |
|                    | -   A maximum of 50 files per upload.           |
|                    |                                                 |
|                    | -   Supported file types: .jpg, .jpeg, .png,    |
|                    |     .pdf, .zip, .msg                            |
|                    |                                                 |
|                    | -   Supported characters in upload file names:  |
|                    |     alphanumeric, space, hyphen, underscore,    |
|                    |     period.                                     |
+--------------------+-------------------------------------------------+
| **Remarks to**     | This field is optional. However, it is          |
| **approver**       | recommended to specify your reasons for seeking |
|                    | approval.\                                      |
|                    | For example, requesting approval to subscribe   |
|                    | to SHIP-HATS for Project X.                     |
+--------------------+-------------------------------------------------+

**10.** Make sure the information displayed on this page is correct and
click **Submit.**

Notes:

-   To edit your inputs, go to the required tab and click **Edit.**

-   To download a summary of the form, click **Download summary.**

**11.** In the **Submit for approval** pop-up window, review the terms
and conditions, select all **checkboxes** and click **Submit.**

\<submit1.png\>

\<submit2.png\>

## Approve or reject a system creation request

## Configure products

**Next steps:**

Invite users
