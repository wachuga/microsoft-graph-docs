---
title: "Get accessPackageAssignmentPolicy"
description: "Read the properties and relationships of an accessPackageAssignmentPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get accessPackageAssignmentPolicy
Namespace: microsoft.graph

Read the properties and relationships of an [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
GET /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/accessPackageAssignmentPolicy
GET /identityGovernance/entitlementManagement/accessPackageCatalogs/{accessPackageCatalogId}/accessPackages/{accessPackageId}/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and an [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_accesspackageassignmentpolicy"
}
-->
``` http
GET https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentPolicy"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentPolicy",
    "id": "389463c9-63c9-3894-c963-9438c9639438",
    "accessPackageId": "String",
    "displayName": "String",
    "description": "String",
    "canExtend": "Boolean",
    "durationInDays": "Integer",
    "expirationDateTime": "String (timestamp)",
    "createdBy": "String",
    "createdDateTime": "String (timestamp)",
    "modifiedBy": "String",
    "modifiedDateTime": "String (timestamp)",
    "questions": [
      {
        "@odata.type": "microsoft.graph.accessPackageMultipleChoiceQuestion"
      }
    ],
    "requestorSettings": {
      "@odata.type": "microsoft.graph.requestorSettings"
    },
    "requestApprovalSettings": {
      "@odata.type": "microsoft.graph.approvalSettings"
    },
    "accessReviewSettings": {
      "@odata.type": "microsoft.graph.assignmentReviewSettings"
    }
  }
}
```
