﻿---
title: DSCPInbound element (QualityEndPointType complexType) 
TOCTitle: DSCPInbound element
ms:assetid: 43df1365-0092-d7cf-daf1-48c6ae037399
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt170852(v=office.16)
ms:contentKeyID: 65855425
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# DSCPInbound element 

(QualityEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

QoS category marking when the stream is received on this endpoint. This field is populated only from Skype for Business clients newer than Skype for Business 2013.


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
<td><p>xs:boolean</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="DSCPInbound"  type="xs:boolean" minOccurs="0">
    
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
<td><p><a href="from-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">From</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>The source of the reported media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="to-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">To</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>Destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

