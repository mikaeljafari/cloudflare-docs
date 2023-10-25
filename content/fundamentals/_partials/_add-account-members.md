---
_build:
  publishResources: false
  render: never
  list: never
---

{{<tabs labels="Dashboard | API">}}
{{<tab label="dashboard" no-code="true">}}
 
To add a member to your account:

1. Log in to the [Cloudflare dashboard](https://dash.cloudflare.com/login) and select your account.
2. Go to **Manage Account** > **Members**.
3. Select **Invite**.
4. Fill out the following information:

    - **Invite members**: Enter one or more email addresses (if multiple, separate addresses with commas).
    - **Scope**: Use a variety of fields to adjust the [scope](/fundamentals/setup/manage-members/roles/) of your roles.
    - **Roles**: Choose one or more [roles](/fundamentals/setup/manage-members/roles/) to assign your members.

5. Select **Continue to summary**.
6. Review the information, then select **Invite**.

{{<Aside type="note">}}
If a user already has an account with Cloudflare and you have an Enterprise account, you can also select **Direct Add** to add them to your account without sending an email invitation.
{{</Aside>}}
 
{{</tab>}}
{{<tab label="api" no-code="true">}}
 
To add a member using the API, send a [`POST` request](/api/operations/account-members-add-member).
 
{{</tab>}}
{{</tabs>}}