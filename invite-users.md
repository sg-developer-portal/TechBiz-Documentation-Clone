# Invite users

Public officers and vendors need to have a [TechPass](https://www.developer.tech.gov.sg/products/categories/digital-identity/techpass/overview.html) account to access [Singapore Government Tech Stack(SGTS)](https://www.developer.tech.gov.sg/singapore-government-tech-stack/overview/index.html) products. TechBiz allows public officers to send TechPass invites to other public officers or create a TechPass account on behalf of other public officers and vendors.

## Prerequisites

- Public officers with a valid organisation email address such as  *your_name@agency.gov.sg* can invite other public officers or vendors using a [non-SE GSIB](glossary) device.

- Have the following information ready before proceeding:
  - Public officers and vendors who require a TechPass account
    - Organisation email address
    - **First name** and **Last name**
    - **Contact number**
    - **Organisation**
    - **Department** (optional)
    - **TechPass username** (for vendors)

## Invite users to TechPass

1.  [Log in to TechBiz portal.](log-in-to-TechBiz-portal.md)

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

2. Select **Download Original**.

3. Open the downloaded xlsx file, specify the required details and save the file.

4. In **Upload user list** section, select **Choose a file**.

5. Select the saved file and upload it.
A success message with the user list is displayed.

<kbd>![approv_2](/images/batch_upload_3.png)</kbd>

  - To view or edit user details, click the ellipsis on the row and click **View details**.

  - To delete a single user, click **Remove**.

  - To delete all users, click **Reset**. To confirm reset, click **Confirm**.


>**Notes:**
>
>When an invitation is unuccessful, you will receive an error notification during submission. You need to do the following:
>
>- To troubleshoot [email invitation](#email-invitation) or [create account](#create-account) issues:
>    - Raise a service request by clicking on the support email link provided in the error notification and attach the Trace ID.
>- To troubleshoot [batch upload](#batch-upload) issues:
>    1. In the user list of the uploaded file, click the ellipsis on the row with errors.
>    2. Click **View details**.
>    3. Amend the required details and click **Save**.
>    4. Click **Submit**.

> Existing TechPass users can also request for SEED provisioning.
> - If you are a public officer, click [Onboard to SEED](https://docs.developer.tech.gov.sg/docs/techpass-user-guide/#/onboard-to-seed) and follow the on-screen instructions.
> - If you are a vendor, raise a [service request](https://go.gov.sg/techpass-sr) in the TechPass service desk.

You can view the list of users you have invited and their status.

To view the list of invited users:

1. [Log in to TechBiz portal.](log-in-to-TechBiz-portal.md)

2. In **Overview**, click **Invite users**. Alternatively, from the left sidebar, go to **Invite Users**.

3. Go to **Invite user status**

The list of users invited and their status will be shown. Their TechPass account and SEED licencing status will be displayed on the list.

<img src="/images/invite_user_status.png" alt="drawing" width="55%"/>

First name and last name is displayed when user has signed up for TechPass or when the account is created through [create account](#create-account) or [batch upload](#batch-upload).