# AD and ADFS Linked Template

Azure:
[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmcrosstx%2FAD_ADFS_Linked%2Fmaster%2Fazuredeploy.json)

Azure US Gov:
[![Deploy to AzureGov](https://azuredeploy.net/deploybutton.png)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmcrosstx%2FAD_ADFS_Linked%2Fmaster%2Fazuredeploy.json)

This Template deploys the server and network components for an Active Directory and Public facing ADFS setup. Some components are optional and can be disabled when deploying the template.

Components:
* 2 x Domain Controllers
* 2 x ADFS Servers
* 2 x WAP Servers
* 1 x AAD Connect Server

Optional:
* 2 x Exchange Servers
* 1 x AAD Connect SQL Server

Requirements:

You will need to have a VNet already setup with the appropriate subnets you would like to use for each set of servers. You will also need to have the Resource Groups already provisioned.
