# Azure-DeployUmbraco
Deploy Umbraco Package to Azure

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FZaid-Safadi%2FAzure-DeployUmbraco%2Fmaster%2Fazuredeploy.json"><img src="https://camo.githubusercontent.com/9285dd3998997a0835869065bb15e5d500475034/687474703a2f2f617a7572656465706c6f792e6e65742f6465706c6f79627574746f6e2e706e67" data-canonical-src="http://azuredeploy.net/deploybutton.png" style="max-width:100%;"></a> <a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FZaid-Safadi%2FAzure-DeployUmbraco%2Fmaster%2Fazuredeploy.json">
    <img src="https://camo.githubusercontent.com/536ab4f9bc823c2e0ce72fb610aafda57d8c6c12/687474703a2f2f61726d76697a2e696f2f76697375616c697a65627574746f6e2e706e67" data-canonical-src="http://armviz.io/visualizebutton.png" style="max-width:100%;">
</a>

## Included Azure Resources
Azure Hosting Plan 
Azure Website

## Description
Current Umbraco version of deployed Package: 7.4.2
This is the simplest deployment package of Umbraco to Azure. It only creates a Resource Group, Azure Hosting Plan and Azure website then deploy an Umbraco package that I created. 

The package deployed is a custom package I created and copied to a blob storage account. You can deploy your own by providing your package storage location parameters during deployment.

