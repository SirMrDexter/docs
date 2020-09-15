---
title: Create a tenant
description: An example script that creates a tenant.
---

This script demonstrates how to programmatically create a new [tenant](/docs/deployment-patterns/multi-tenant-deployments/index.md) in Octopus.

## Usage

Provide values for:

- Octopus URL
- Octopus API Key
- Name of the space to use
- Name of the tenant to create
- A list of Project names to connect the new tenant with
- A list of Environment names to connect the new tenant with
- A list of Tenant tags to use with the new tenant

## Script

!include <create-a-tenant-scripts>