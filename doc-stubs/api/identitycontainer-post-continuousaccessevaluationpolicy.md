---
title: "Create continuousAccessEvaluationPolicy"
description: "Create a new continuousAccessEvaluationPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create continuousAccessEvaluationPolicy
Namespace: microsoft.graph

Create a new continuousAccessEvaluationPolicy object.

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
POST ** Collection URI for microsoft.graph.continuousAccessEvaluationPolicy not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.

The following table shows the properties that are required when you create the [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|isEnabled|Boolean|**TODO: Add Description**|
|users|String collection|**TODO: Add Description**|
|groups|String collection|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_continuousaccessevaluationpolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.continuousAccessEvaluationPolicy not found
Content-Type: application/json
Content-length: 226

{
  "@odata.type": "#microsoft.graph.continuousAccessEvaluationPolicy",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "users": [
    "String"
  ],
  "groups": [
    "String"
  ]
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.continuousAccessEvaluationPolicy"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.continuousAccessEvaluationPolicy",
  "id": "0ac55316-5316-0ac5-1653-c50a1653c50a",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "users": [
    "String"
  ],
  "groups": [
    "String"
  ]
}
```

