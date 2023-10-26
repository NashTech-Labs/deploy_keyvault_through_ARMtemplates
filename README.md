# Azure Key Vault Deployment
Deploying the key vault through ARM templates in Azure. ARM is also called infrastructure as a code.
## Prerequisites
Before deploying the Azure Key Vault, ensure that you have the following prerequisites:

1. Azure Subscription: You need access to an Azure subscription where you can create resources.

2. Azure CLI: Install the Azure CLI on your local machine. You can download it from here.

3. Azure Resource Group: Create an Azure resource group where the Key Vault will be deployed.

### Deploy your keyvault 
```
az deployment group create --resource-group YourResourceGroup --template-file deployKeyVault.json --parameters parameters.json
```
