Recently I needed to do an API to API authentication flow with Managed
Identity on Azure for App Services. And this post was a very big help
because official Microsoft docs are not always easy to follow.

[
https://awh.net/insights/post?post=securing-api-to-api-azure-app-services-using-managed-identity](https://awh.net/insights/post?post=securing-api-to-api-azure-app-services-using-managed-identity)

There is just one difference. For the `TokenRequestContext` I had to use
the "Authentication >  Registered Apps > Expose an API > **Application ID
URI**" to get the actual token.

Paweł
