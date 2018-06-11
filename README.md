# AD and ADFS Linked Template

[COM:![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/mcrosstx/AD_ADFS_Linked/blob/master/AD_ADFS_Linked.json)

[GOV:![Deploy to AzureGov](https://azuredeploy.net/deploybutton.png)](https://portal.azure.us/#create/Microsoft.Template/uri/https://github.com/mcrosstx/AD_ADFS_Linked/blob/master/AD_ADFS_Linked.json)

This Template deploys the server and network components for an Active Directory and Public facing ADFS setup.

Components:
* 2 x Domain Controllers
* 2 x ADFS Servers
* 2 x WAP Servers
* 2 x Exchange Servers
* 1 x AAD Connect Server
* 1 x AAD Connect SQL Server

Requirements:

You will need to have a VNet already setup with the appropriate subnets you would like to use for each set of servers. You will also need to have the Resource Groups already provisioned.
