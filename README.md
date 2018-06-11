# AD and ADFS Linked Template

[COM:![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/mcrosstx/AD_ADFS_Linked/master/azuredeploy.json)

[GOV:![Deploy to AzureGov](https://azuredeploy.net/deploybutton.png)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2mcrosstx%2FAD_ADFS_Linked%2Fmaster%2Fazuredeploy.json)

<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2mcrosstx%2FAD_ADFS_Linked%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkylgrn%2FAzure_Gov_PAN-2Firewalls-Public-load-balancer%2Fmaster%2FAzure_Gov_PAN-2Firewalls-Public-load-balancer%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

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
