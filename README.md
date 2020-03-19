# Azure Blueprints sample files for deploying Azure Blueprints as code. 
Guiding Blog Post and Video (Azure Advent Calendar): https://www.wesleyhaakman.org/azure-advent-calendar-azure-blueprints/

Usage:
Clone the repository and modify the ID's to match your Subscription or Management group:

The ID depends on whether the Blueprint is stored on a subscription level or on a Management Group level and is build up as follows:

Blueprint ID on a ManagementGroup Level
/providers/Microsoft.Management/managementGroups/*myManagementGroupId*/providers/Microsoft.Blueprint/blueprints/BlueprintName

Blueprint ID on a Subscription Level
/subscriptions/*SubscriptionID*/providers/Microsoft.Blueprint/blueprints/BlueprintName