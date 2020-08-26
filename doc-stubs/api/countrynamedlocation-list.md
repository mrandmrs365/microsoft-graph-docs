---
title: "List countryNamedLocations"
description: "Get a list of the countryNamedLocation objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List countryNamedLocations
Namespace: microsoft.graph

Get a list of the [countryNamedLocation](../resources/countrynamedlocation.md) objects and their properties.

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
GET /countryNamedLocations
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

If successful, this method returns a `200 OK` response code and a collection of [countryNamedLocation](../resources/countrynamedlocation.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_countrynamedlocation"
}
-->
``` http
GET https://graph.microsoft.com/beta/countryNamedLocations
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.countryNamedLocation)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.countryNamedLocation",
      "id": "fad51dbd-1dbd-fad5-bd1d-d5fabd1dd5fa",
      "displayName": "String",
      "createdDateTime": "String (timestamp)",
      "modifiedDateTime": "String (timestamp)",
      "countriesAndRegions": [
        "String"
      ],
      "includeUnknownCountriesAndRegions": "Boolean",
      "countryLookupMethod": "String"
    }
  ]
}
```

