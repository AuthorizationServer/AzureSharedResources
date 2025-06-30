# Azure Shared Resources

This repository contains Infrastructure as Code (IaC) for provisioning shared Azure resources such as Application Insights, Log Analytics Workspace, and others. In a typical enterprise deployment, these resources are already provisioned and managed by multiple teams. To use existing resources in your enterprise, modify authorization-server@2025-06-27.bicep file under authsvr folder in AzureBicep repo in your fork.

## Resources Provisioned

The following shared resources are created by `Iaac\azure-resources.bicep`:

- Application Insights
- Log Analytics Workspace



