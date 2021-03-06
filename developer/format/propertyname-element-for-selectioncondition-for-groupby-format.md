---
title: "PropertyName Element for SelectionCondition for GroupBy (Format) | Microsoft Docs"
ms.custom: ""
ms.date: "09/13/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: d1707317-6c26-4866-bcc1-8924103c9014
caps.latest.revision: 6
---
# PropertyName Element for SelectionCondition for GroupBy (Format)

Specifies the .NET property that triggers the condition. When this property is present or when it evaluates to `true`, the condition is met, and the definition is used. This element is used when defining how a new group of objects is displayed.

Configuration Element (Format)
ViewDefinitions Element (Format)
View Element (Format)
GroupBy Element for View (Format)
CustomControl Element for GroupBy (Format)
CustomEntries Element for CustomControl for GroupBy (Format)
CustomEntry Element for CustomControl for GroupBy (Format)
EntrySelectedBy Element for CustomEntry for GroupBy (Format)
SelectionCondition Element for EntrySelectedBy for GroupBy (Format)
PropertyName Element for SelectionCondition for GroupBy (Format)

## Syntax

```xml
<PropertyName>.NetTypeProperty</PropertyName>
```

## Attributes and Elements

The following sections describe attributes, child elements, and the parent element of the `PropertyName` element.

### Attributes

None.

### Child Elements

None.

### Parent Elements

|Element|Description|
|-------------|-----------------|
|[SelectionCondition Element for EntrySelectedBy for GroupBy (Format)](./selectioncondition-element-for-entryselectedby-for-groupby-format.md)|Defines a condition that must exist for the control definition to be used.|

## Text Value

Specify the .NET property name.

## Remarks

The selection condition must specify a least one property name or a script, but cannot specify both. For more information about how selection conditions can be used, see [Defining Conditions for Displaying Data](./defining-conditions-for-displaying-data.md).

## See Also

[SelectionCondition Element for EntrySelectedBy for GroupBy (Format)](./selectioncondition-element-for-entryselectedby-for-groupby-format.md)

[Writing a Windows PowerShell Formatting File](./writing-a-windows-powershell-formatting-file.md)
