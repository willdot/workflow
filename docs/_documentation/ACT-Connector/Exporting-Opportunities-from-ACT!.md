---
slug: exporting-opportunities-from-act
redirect_from: "/article/143-exporting-opportunities-from-act"
title: Exporting Opportunities from ACT!
---
This task will export Opportunities from ACT! into [ACT! Opportunity XML](act-opportunity-xml).

This task requires a Connection to ACT!, for more information on setting up and managing ACT! connections, see 	[Connecting to ACT!](connecting-to-act).

## Connection Settings
### ACT! Connection  
_Required_  
The ACT! Connection to export Opportunities from. See the [Connecting to ACT!](connecting-to-act) page if you require more information on how to create/manage Zynk Connections to ACT!.  
Defaulted to the connection marked as the default for ACT!. For more information on managing default connections within Zynk, see the [Connection Manager](connection-manager) page.

## Export Settings
### Export All
_Required_  
Set to `false` to only export ACT! Opportunities that have been modified since the last export.  
Set to `true` to always export all ACT! Opportunities.  
Defaulted to `false`.

### Filter File
_Optional_  
An absolute or relative file path to the ACT! Query file (qry) containing the ACT! Opportunity custom filter to use when exporting data. The filter file should be created via ACT!. See the [Zynk Objects](zynk-objects) page if you require more information on how the Zynk Object file value works.  
Defaulted to `empty`.

### Opportunity Custom Fields
_Optional_  
List of additional fields to export from the ACT! Opportunities.  
These should be the provided as a field per line in the list and the name provided should be the 'Field Name' as it appears in ACT!.  
Defaulted to `empty`.

## File Settings
### Output File
_Required_  
An absolute or relative file path on the local computer or network to save any Opportunities which were exported from ACT! to. See the [Zynk Objects](zynk-objects) page if you require more information on how the Zynk Object file value works.  
Defaulted to `act_export_opportunities.xml` in the current working directory.

## Zynk Settings
See [Common Task Settings](common-task-settings).

## Articles and Sample Files
For full documentation and samples, see [ACT! Opportunity XML](act-opportunity-xml).

## Links
- [Introduction to the ACT! Connector](act)
- [Connecting to ACT!](connecting-to-act)
- [Importing Companies into ACT!](importing-companies-into-act)
- [Exporting Companies from ACT!](exporting-companies-from-act)
- [Importing Contacts into ACT!](importing-contacts-into-act)
- [Exporting Contacts from ACT!](exporting-contacts-from-act)
- [Importing Opportunities into ACT!](importing-opportunities-into-act)
- [Exporting Opportunities from ACT!](exporting-opportunities-from-act)
- [Importing Products into ACT!](importing-products-into-act)
- [Exporting Products from ACT!](exporting-products-from-act)