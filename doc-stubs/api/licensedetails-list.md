---
title: "List licenseDetails"
description: "Get a list of the licenseDetails objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List licenseDetails
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [licenseDetails](../resources/licensedetails.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
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
GET /me/licenseDetails
GET /users/{usersId}/licenseDetails
GET /servicePrincipals/{servicePrincipalsId}/licenseDetails
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

If successful, this method returns a `200 OK` response code and a collection of [licenseDetails](../resources/licensedetails.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_licensedetails"
}
-->
``` http
GET https://graph.microsoft.com/beta/me/licenseDetails
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.DirectoryServices.licenseDetails)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.DirectoryServices.licenseDetails",
      "id": "58b6aa4e-aa4e-58b6-4eaa-b6584eaab658",
      "servicePlans": [
        {
          "@odata.type": "microsoft.graph.servicePlanInfo"
        }
      ],
      "skuId": "Guid",
      "skuPartNumber": "String"
    }
  ]
}
```
