# ARM template and template spec

This repo is intend to study the ARM template modulation. 

ARM template doesn't support modulation with local file system. This means  sub-templates have to be uploaded to a storage account or repo like Github to be [linked into the main template](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-tutorial-linked-template?tabs=azure-powershell).

An alternative approach is to [create a link template spec](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs-create-linked?tabs=azure-powershell) resource in a resource group. Template spec packs then main template and all linked templates as a resource in the resource group.

