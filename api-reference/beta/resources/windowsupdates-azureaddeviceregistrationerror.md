---
title: "azureADDeviceRegistrationError resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# azureADDeviceRegistrationError resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

An error in an Azure AD device's registration process that prevents the device from being enrollment in update management or receiving deployed content.


Inherits from [updatableAssetError](../resources/windowsupdates-updatableasseterror.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|A description of the error. Inherited from [updatableAssetError](../resources/windowsupdates-updatableasseterror.md)|
|reason|azureADDeviceRegistrationErrorReason|The reason why the registration encountered an error. Possible values are: `invalidGlobalDeviceId`, `invalidAzureADDeviceId`, `missingTrustType`, `invalidAzureADJoin`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsUpdates.azureADDeviceRegistrationError"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.azureADDeviceRegistrationError",
  "description": "String",
  "reason": "String"
}
```
