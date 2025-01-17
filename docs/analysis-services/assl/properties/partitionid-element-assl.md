---
title: "PartitionID Element (ASSL) | Microsoft Docs"
description: Learn about the PartitionID property element in the Analysis Services Scripting Language (ASSL) schema.
ms.date: 7/25/2018
ms.prod: sql
ms.custom: assl
ms.reviewer: owend
ms.technology: analysis-services
ms.topic: reference
author: minewiskan
ms.author: owend

---
# PartitionID Element (ASSL)

  Associates a [Partition](../objects/partition-element-assl.md) element with a parent element, binding, or out-of-line binding.  
  
## Syntax  
  
```xml  
  
<PartitionBinding>  
   ...  
   <PartitionID>...</PartitionID>  
   ...  
</PartitionBinding>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|String|  
|Default value|None|  
|Cardinality|1-1: Required element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[PartitionBinding](../data-type/partitionbinding-data-type-assl.md)|  
|Child elements|None|  
  
## Remarks  

  
