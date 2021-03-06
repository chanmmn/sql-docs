---
title: "AllMemberName Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "AllMemberName Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "AllMemberName"
helpviewer_keywords: 
  - "AllMemberName element"
ms.assetid: 5fda5563-cb7a-4402-82ad-3d6c432b6a7e
caps.latest.revision: 39
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# AllMemberName Element (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Contains the caption in the default language for the All member of a [Hierarchy](../../../analysis-services/scripting/objects/hierarchy-element-assl.md) element.  
  
## Syntax  
  
```xml  
  
<Hierarchy>  
      ...  
      <AllMemberName>...</AllMemberName>  
   ...  
</Dimension>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|String|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[Hierarchy](../../../analysis-services/scripting/objects/hierarchy-element-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The element that corresponds to the parent of **AllMemberName** in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.Hierarchy>.  
  
## See Also  
 [Properties &#40;ASSL&#41;](../../../analysis-services/scripting/properties/properties-assl.md)  
  
  
