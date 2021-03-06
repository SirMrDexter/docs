---
title: How to Create an API Key
description: How to create an API key to interact with Octopus without the need for a username and password.
position: 10
---

API keys allow you to access the Octopus Deploy [REST API](/docs/octopus-rest-api/index.md) and perform tasks such as creating and deploying releases. API keys can be saved in scripts or external tools, without having to use your username and password. Each user and service account can have multiple API keys.

See the [Service Accounts docs](/docs/security/users-and-teams/service-accounts.md) for information about creating service accounts.

## Creating an API Key {#HowtocreateanAPIkey-CreatinganAPIkey}

<iframe width="560" height="315" src="https://www.youtube.com/embed/f3-vRjpB0cE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You can create API keys by performing the following steps:

1. Log into the Octopus Web Portal, click your profile image and select **Profile**.
1. Click **My API Keys**.
1. Click **New API key**, state the purpose of the API key and click **Generate new**.
1. Copy the new API key to your clipboard.

:::warning
**Write Your Key Down**
After you generate an API key, it cannot be retrieved from the Octopus Web Portal again, we store only a one-way hash of the API key. If you want to use the API key again, you need to store it in a secure place such as a password manager. Read about [why we hash API keys](https://octopus.com/blog/hashing-api-keys).
:::
