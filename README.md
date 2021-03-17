# ARM Template - Telco Edge Node

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMounikaaakurathi%2FEdgeNode-DeploymentTelco%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>

This Template creates the following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hubs
4. Log Analytics workspace
5. Redis Cache
 
Create a resource group with below command

PS> New-AzureRmResourceGroup -Name <Resource-Group-Name> -Location <Azure-Region>
    
E.g. New-AzureRmResourceGroup -Name Prod-Tel-SI-RG-AKS-XYZ-01 -Location "Central India"

The purpose of this template is to deploy an AKS cluster with all of dependent resources.
