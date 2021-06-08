---
title: "serviceHealthIssuePost resource type"
description: "This complex type represents a historical post in a service health issue."
author: "payiAzure"
localization_priority: Normal
ms.prod: "service communications"
doc_type: resourcePageType
---

# serviceHealthIssuePost resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

This complex type represents a historical post in a service health issue.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|The published time of the post|
|description|[itemBody](../resources/itembody.md)|The content of the service issue post|
|postType|postType|The post type of the service issue historical post. Possible values are: `regular`, `quick`, `strategic`, `unknownFutureValue`.|

## Relationships
This resource type doesn't have relationships.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.serviceHealthIssuePost"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.serviceHealthIssuePost",
  "createdDateTime": "String (timestamp)",
  "postType": "String",
  "description": {
    "@odata.type": "microsoft.graph.itemBody"
  }
}
```
