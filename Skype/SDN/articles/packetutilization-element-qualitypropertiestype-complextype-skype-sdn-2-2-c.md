﻿---
title: PacketUtilization element (QualityPropertiesType complexType) 
TOCTitle: PacketUtilization element
ms:assetid: 89d76513-d3bf-ba22-e97d-25d9a1d01978
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt404809(v=office.16)
ms:contentKeyID: 68250721
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# PacketUtilization element 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Number of Real-time Transport Protocol (RTP) packets received in the session. This metric is reported for all available modalities and media types.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:string</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="PacketUtilization"  type="xs:string">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

