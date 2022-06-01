# Invite users

**Prerequisite**:

-   Users (public officers and vendors) need to have a TechPass account to access [Singapore Government Tech Stack(SGTS)](https://www.developer.tech.gov.sg/singapore-government-tech-stack/overview/index.html) products in TechBiz.

This guide shows you how agencies can send TechPass invites to users from the TechBiz portal.

## To invite users to TechPass:

**Prerequisites:**

-   A public officer with a valid organisation email (for example, <user_name@agency.gov.sg>)

-   Non-SE GSIB (Government Standard Image Build) device.

1.  [Log in to the TechBiz portal.](log_in_to_TechBiz_portal.md)

2.  In the **Overview** page, click **invite users.** Alternatively, from the left sidebar, click **Invite Users.**

![Display Overview](/images/log_in_withotp_overview_otp.png)

3.  Select the required **invitation type.**

| **Invitation type** | **When to use**
|---- |----
| [Email invitation](#email-invitation)| To send email invites to public officers.
| [Create account](#create-account) | To create TechPass accounts on behalf of public officers and vendors.
| [Batch upload](#batch-upload)| To create TechPass accounts for multiple users (public officers and vendors).

![Display Invitation type](/images/invitation_type.png)

### Email invitation

Specify the invitation email details and click **Submit.**

> **Note:** Unless mentioned otherwise, all fields are mandatory.

| Field name | Description and usage|
|---- |----
| **Email address**| Enter the email address of the user who requires a TechPass account. This should be a valid organisation email. Format of this email address is user_name@agency.gov.sg For example, user_name@tech.gov.sg.
I Is onboarding to **SEED** required? | Select Yes if the user needs to access SGTS services from an internet device, that requires SEED compliance. Select **No** if user needs to access SGTS services from a Government Standard Image Build (GSIB) device.
| Reason | Enter the reason why you need a TechPass account.

![Display Invitation Type](/images/email_invite.png)

### Create account

Specify the TechPass account details and click **Submit.**

| Field name | Description and usage|
|---- |----
| **Email address**| Enter the email address of the user who requires a TechPass account. This should be a valid organisation email. Format of this email address is user_name@agency.gov.sg For example, user_name@tech.gov.sg.
| TechPass username | This field is required if user is a vendor. Enter username. 
**Note:** If the user is a public officer, then their official email address will be their TechPass username, so the field will be greyed out and cannot be edited.
|First Name, Last Name, Contact Number, Organisation, Department | Enter user details.
| Is onboarding to **SEED** required? | Select Yes if the user needs to access SGTS services from an internet device, that requires SEED compliance. Select **No** if user needs to access SGTS services from a Government Standard Image Build (GSIB) device.
| Reason | Enter the reason why you need a TechPass account.

![Display Create account](/images/create_account.png)

### Batch upload

1.  Click **Download excel template link.**

> **Note:** The template is a csv file.

![Display Batch upload](/images/batch_upload_1.png)


2.  Specify the **user details** and save the file.
3.  To upload the file, click **Choose a file.**

![Display Batch upload](/images/batch_upload_2.png)

4.  Select the **file** and upload it. A confirmation message **Uploaded \<filename\>.csv** along with the user details appears.
5.  To **view or delete** user details from the file, click the ellipsis on the row.

![Display Batch upload](/images/batch_upload_3.png)

6.  To reset user details, click **Reset.** To confirm reset, in the dialog, click **Confirm.**


