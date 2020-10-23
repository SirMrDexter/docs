---
title: Project triggers
description: Project Triggers allow you to define unattended behavior for your project such as automatically deploying a release to an environment.
position: 40
---

Project triggers allow you to define an unattended behavior for your [Projects](/docs/projects/index.md).

Project triggers allow you to choose from a subset of **events** that can occur in Octopus Deploy, apply a **filter** to those events, and decide on an **action** you want performed once the trigger fires. The example below shows an automatic deployment trigger configured to fire when a [deployment target](/docs/infrastructure/index.md) that belongs to the **Production** [environment](/docs/infrastructure/environments/index.md) becomes available, and has the **web-server** [target role](/docs/infrastructure/deployment-targets/index.md#target-roles).

![](images/octopus-triggers-diagram.png "width=500")

:::success
We have written a [comprehensive guide](/docs/deployment-patterns/elastic-and-transient-environments/index.md) about using project triggers with a focus on deploying to elastic and transient environments.
:::
