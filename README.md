# Azure Platform Live - Dev

This repository contains the Terraform configuration for the training Azure
platform environment. It composes the published resource-group and network
modules to manage the development resource group, virtual network, and subnets.

## HCP Terraform

- **Workspace:** `azure-platform-dev`
- **Working directory:** `environments/dev`
- **Applies:** Auto-apply is disabled. Review each plan and manually confirm an
  apply in HCP Terraform.

## Local commands

Local Terraform commands are for formatting, initialization, and validation
only. This configuration is not connected to the HCP workspace's remote state,
so local commands do not deploy or change Azure resources. Review and apply
infrastructure changes through the HCP Terraform workspace.
