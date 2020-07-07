# Azure Kubernetes and dependencies Deployment Template

<a href="https://azuredeploy.net/" target="_blank">
    <img src="https://azurecomcdn.azureedge.net/mediahandler/acomblog/media/Default/blog/deploybutton.png"/>
</a>

This ARM Template creates following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hubs
4. Log Analytics workspace
5. Redis Cache
 
Create a resource group with below command on PowerShell:

PS> New-AzureRmResourceGroup -Name TBS-Tel-SI-RG-AKS-01 -Location "Region-Name"

The purpose of this template is to deploy AKS cluster with all dependent resources.
