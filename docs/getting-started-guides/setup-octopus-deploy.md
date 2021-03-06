---
title: Setup Octopus Deploy
description: Learn how to setup an instance Octopus Deploy self-hosted server or Octopus Cloud.
position: 30
---

Octopus deploy is available in two variants:

- [Self-hosted Octopus Server](#self-hosted-octopus-server) that you host on the infrastructure of your choice. 
- [Octopus Cloud](#octopus-cloud) which is the hosted version of Octopus Deploy.

## Self-hosted Octopus Server

<iframe width="560" height="315" src="https://www.youtube.com/embed/6H8g8vFmzWM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you want to host the Octopus Server on infrastructure of your choosing, you can download the installer, install the server, and manage it on infrastructure of your choice, providing it meets the installation [requirements](/docs/installation/requirements.md). 

You will also need to maintain the server, backup the database, and apply upgrades. 

### Install the self-hosted Octopus Server

To install the Octopus Server on a [supported Windows Server](/docs/installation/requirements.md#windows-server), complete the following steps:

1. [Download](https://octopus.com/downloads) the Octopus Deploy installer.
1. Start the installer and follow the setup wizard prompts.
1. Click **Finish** to exit the installer and grant **Octopus.Manager.Server** permission to make changes to your device.
1. Click **Get started...**, follow the on-screen instructions, and accept the defaults.
1. On the **Database** page, follow the instructions to download and install SQL Server Express.
1. Click the drop-down arrow in the **Server Name** field to detect the SQL Server database. Octopus will create the database for you.
1. Continue to follow the prompts, and click **Finished** when the installation has completed.

Your self-hosted Octopus Server is now ready to use.

Before you do anything else, click the **View Master Key** link, copy your Master Key, and store it somewhere safe.

To launch the Octopus Web Portal, click **Open in browser** from the **Octopus Manager** and log in with the credentials you configured during the installation process.

:::success
For more information and other installation options, see the [installation documentation](/docs/installation/index.md).
:::

Now that you've installed the self-hosted Octopus Server, it's time to explore the [Octopus Web Portal](/docs/getting-started-guides/the-octopus-web-portal.md).

## Octopus Cloud

Octopus Cloud is the hosted version of Octopus. We host the Octopus Server on your behalf and take responsibility for the underlying infrastructure and upgrading the server so you are using the latest features of the platform.

### Create an Octopus Cloud instance

To create an Octopus Cloud instance, you need to first create an Octopus account, and then you can create your Octopus Cloud instance:

!include <octopus-account>
!include <octopus-cloud-instance>

When your Octopus Cloud instance is ready, you can log in at the URL you defined during the registration process: `<yoururl>.octopus.app`.

:::success
To learn more about Octopus Cloud, see the [Octopus Cloud documentation](/docs/octopus-cloud/index.md).
:::

Now that you've created an Octopus Cloud instance, it's time to explore the [Octopus Web Portal](/docs/getting-started-guides/the-octopus-web-portal.md) or you can return to the [getting started guides](/docs/getting-started-guides/index.md).