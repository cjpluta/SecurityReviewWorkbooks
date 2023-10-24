# Security Review Workbook

This workbook focues on reporting security-related configurations for resources that are deployed in Azure subscriptions. The resouce types that are currently supported in the Azure Security Workbooks include:
  - Storage accounts
  - Azure Kubernetes Service
  - Azure Container Registry
  - Azure SQL Database

## Prerequisites

Thee workbooks assume that you have the appropriate permissions to deploy Azure Monitor workbooks, and read the configuration of the resources in the subscription. If you do not have read permissions, workbooks might be blank or contain incomplete data. 

## Deploy

This Security Review workbook consists of several Azure Monitor workbooks. You can deploy these to your Azure Subscription in any Resource Group. Currently, copy the Workbook code into the advanced editor of a workbook. 

## Roadmap
To-do list:

**Usability**
  - Auto-deploy template
  - Import workbooks as tabs in a single view

**Additional resource types**
  - Virtual Machines and VMSS
  - Networking
  - App Services / Functions
  - API Management
  - Identity
  - Key Vault
  - Application Gateway

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
