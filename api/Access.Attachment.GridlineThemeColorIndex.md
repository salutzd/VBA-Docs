---
title: Attachment.GridlineThemeColorIndex Property (Access)
keywords: vbaac10.chm14635
f1_keywords:
- vbaac10.chm14635
ms.prod: access
api_name:
- Access.Attachment.GridlineThemeColorIndex
ms.assetid: 195122c2-c972-8d39-aea6-bf2b531b1f84
ms.date: 06/08/2017
---


# Attachment.GridlineThemeColorIndex Property (Access)

Gets or sets the theme color index that represents a color in the applied color theme associated with the  **GridlineColor** property of the specified object. Read/write **Long**.


## Syntax

 _expression_. `GridlineThemeColorIndex`

 _expression_ A variable that represents an [Attachment](Access.Attachment.md) object.


## Remarks

The  **GridlineThemeColorIndex** property uses one of the values listed in the following table.



|**Value**|**Description**|
|:-----|:-----|
|0 |Text 1|
|1 (Default)|Background 1|
|2|Text 2|
|3|Background 2|
|4|Accent 1|
|5|Accent 2|
|6|Accent 3|
|7|Accent 4|
|8|Accent 5|
|9|Accent 6|
|10|Hyperlink|
|11|Followed Hyperlink|

If no theme is applied, the  **GridlineThemeColorIndex** property contains -1.

This property is not surfaced in the property sheet. 


## See also


[Attachment Object](Access.Attachment.md)

