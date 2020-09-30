---
title: "accessPackageSubject resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageSubject resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List requestor](../api/accesspackageassignmentrequest-list-requestor.md)|[accessPackageSubject](../resources/accesspackagesubject.md) collection|Get the accessPackageSubject resources from the requestor navigation property.|
|[Create requestor](../api/accesspackageassignmentrequest-post-requestor.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Create a new accessPackageSubject object.|
|[Update requestor](../api/accesspackageassignmentrequest-update-requestor.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Update the properties of a requestor object.|
|[Get requestor](../api/accesspackageassignmentrequest-get-accesspackagesubject.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Read the properties and relationships of an [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[Delete requestor](../api/accesspackageassignmentrequest-delete-requestor.md)|None|Delete an [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[List accessPackageSubjects](../api/accesspackagesubject-list.md)|[accessPackageSubject](../resources/accesspackagesubject.md) collection|Get a list of the [accessPackageSubject](../resources/accesspackagesubject.md) objects and their properties.|
|[Create accessPackageSubject](../api/accesspackagesubject-create.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Create a new [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[Get accessPackageSubject](../api/accesspackagesubject-get.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Read the properties and relationships of an [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[Update accessPackageSubject](../api/accesspackagesubject-update.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Update the properties of an [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[Delete accessPackageSubject](../api/accesspackagesubject-delete.md)|None|Deletes an [accessPackageSubject](../resources/accesspackagesubject.md) object.|
|[List connectedOrganization](../api/accesspackagesubject-list-connectedorganization.md)|[connectedOrganization](../resources/connectedorganization.md) collection|Get the connectedOrganization resources from the connectedOrganization navigation property.|
|[Add connectedOrganization](../api/accesspackagesubject-post-connectedorganization.md)|[connectedOrganization](../resources/connectedorganization.md)|Add connectedOrganization by posting to the connectedOrganization collection.|
|[Remove connectedOrganization](../api/accesspackagesubject-delete-connectedorganization.md)|None|Remove a [connectedOrganization](../resources/connectedorganization.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|altSecId|String|**TODO: Add Description**|
|connectedOrganizationId|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|email|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|objectId|String|**TODO: Add Description**|
|onPremisesSecurityIdentifier|String|**TODO: Add Description**|
|principalName|String|**TODO: Add Description**|
|type|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|connectedOrganization|[connectedOrganization](../resources/connectedorganization.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageSubject",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageSubject",
  "id": "String (identifier)",
  "objectId": "String",
  "altSecId": "String",
  "displayName": "String",
  "principalName": "String",
  "email": "String",
  "onPremisesSecurityIdentifier": "String",
  "type": "String",
  "connectedOrganizationId": "String"
}
```
