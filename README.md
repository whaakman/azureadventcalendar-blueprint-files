# Azure Blueprints sample files for deploying Azure Blueprints as code. 
This sample was written for the [Azure Advent Calendar](https://azureadventcalendar.com/). The guiding Blog Post and Video can be found [here](https://www.wesleyhaakman.org/azure-advent-calendar-azure-blueprints/)

### Usage
1. Watch the video [here](https://www.youtube.com/watch?v=RdtCm8C_PzI&feature=emb_title)

2. Clone this repository

3. update the ID's in the assignment file to match the blueprint you published

    The ID depends on whether the Blueprint is stored on a subscription level or on a Management Group level and is build up as follows:

    *Blueprint ID on a ManagementGroup Level*
    /providers/Microsoft.Management/managementGroups/**myManagementGroupId**/providers/Microsoft.Blueprint/blueprints/BlueprintName
    
    *Blueprint ID on a Subscription Level*
    /subscriptions/**SubscriptionID**/providers/Microsoft.Blueprint/blueprints/BlueprintName
    
4. Have fun!