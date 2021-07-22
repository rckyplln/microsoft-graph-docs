---
title: "Create authenticationMethodsRoot"
description: "Create a new authenticationMethodsRoot object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create authenticationMethodsRoot
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [authenticationMethodsRoot](../resources/authenticationmethodsroot.md) object.

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
POST ** Collection URI for Microsoft.AAD.Reporting.authenticationMethodsRoot not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [authenticationMethodsRoot](../resources/authenticationmethodsroot.md) object.

The following table shows the properties that are required when you create the [authenticationMethodsRoot](../resources/authenticationmethodsroot.md).

|Property|Type|Description|
|:---|:---|:---|



## Response

If successful, this method returns a `201 Created` response code and an [authenticationMethodsRoot](../resources/authenticationmethodsroot.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_authenticationmethodsroot_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for Microsoft.AAD.Reporting.authenticationMethodsRoot not found
Content-Type: application/json
Content-length: 75

{
  "@odata.type": "#Microsoft.AAD.Reporting.authenticationMethodsRoot"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.AAD.Reporting.authenticationMethodsRoot"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.AAD.Reporting.authenticationMethodsRoot"
}
```
