# Invite users

Public officers and vendors need to have a [TechPass](https://www.developer.tech.gov.sg/products/categories/digital-identity/techpass/overview.html) account to access [Singapore Government Tech Stack(SGTS)](https://www.developer.tech.gov.sg/singapore-government-tech-stack/overview/index.html) products. TechBiz allows public officers to send TechPass invites to other public officers or create a TechPass account on behalf of public officers and vendors.

## Prerequisites

- Only a public officer with a valid organisation email address can invite another public officer or vendor. For example, *your_name@agency.gov.sg* using a [non-SE GSIB](glossary) device.

- Have the following information ready before proceeding:
  - Public officers and vendors who require a TechPass account
    - Organisation email address
    - **First name** and **Last name**
    - **Contact number**
    - **Organisation**
    - **Department** (optional)
    - **TechPass username** (for vendors)

## Invite users to TechPass

1.  [Log in to TechBiz portal.](log_in_to_TechBiz_portal.md)

2.  In **Overview**, click **Invite users**. Alternatively, from the left sidebar, click **Invite Users**.

3.  Select the required **invitation type**, enter the required details and click **Submit**.

| <div style="width:270px">Invitation type</div>  | When to use |
| :------------------------------------------ |:-------------|
| [Email invitation](#email-invitation)| To send email invite to a public officer to create a TechPass account.
| [Create account](#create-account) | To create a TechPass account on behalf of a public officer or a vendor.
| [Batch upload](#batch-upload)| To create TechPass accounts for public officers and vendors.

### Email invitation

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address**| Enter the organisation email address of the public officer who requires a TechPass account.
| **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the public officer needs SEED provisioning.<br />Note: SEED provisioning is needed to access SGTS services or products from the Internet device.
| **Reason** | Enter the **Reason** why the public officer needs a TechPass account.

<kbd>![email_invite](/images/email_invite.png ':size=70%')</kbd>

### Create account

Specify the TechPass account details.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address**| Enter the organisation email address of the public officer or vendor who requires a TechPass account.
| **TechPass username** | This field is required if you are requesting TechPass account for a vendor. Enter the required username for the TechPass account.
| **First name,** **Last name,** **Contact number,** **Organisation, and Department**| Enter the required details.<br />Note: **Department** is optional.
| **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the public officer or vendor needs SEED provisioning.<br />Note: SEED provisioning is needed to access SGTS services or products from the Internet device.
| **Reason** | Enter the **Reason** why the public officer or vendor needs a TechPass account.

<kbd>![create_account](/images/create_acct.png)</kbd>

### Batch upload

1. Click **Download excel template link**.

2. Click **Download Original**.

3. Open the downloaded xlsx file, specify the required details and save the file.

4. In **Upload user list** section, click **Choose a file**.

5. Select the saved file and upload it.
A success message with the user list is displayed.

<kbd>![approv_2](/images/batch_upload_3.png)</kbd>

  - To view or edit user details, click the ellipsis on the row and click **View details**.

  - To delete a single user, click **Remove**.

  - To delete all users, click **Reset**. To confirm reset, click **Confirm**.


>**Notes:**
>
>When you proceed to submit details of the required invitation type, you may experience errors.
>
>- To troubleshoot [Email invitation](#email-invitation) or [Create account](#create-account) issues, raise a service request by clicking on the [link](Enquiries_Esuite@tech.gov.sg) provided and attach the Trace ID.
>
>- To troubleshoot [Batch upload](#batch-upload) issues, you need to amend the user details.
>    1. In the user list of the uploaded file, click on the row with errors.
>    2. Click **View details**.
>    3. In the side panel, amend the required details and click **Save**. Click **Submit**.

> Existing TechPass users can also request for SEED provisioning.
> - If you are a public officer, click [Onboard to SEED](https://docs.developer.tech.gov.sg/docs/techpass-user-guide/#/onboard-to-seed) and follow the on-screen instructions.
> - If you are a vendor, raise a [TechPass service request](https://go.gov.sg/techpass-sr).

