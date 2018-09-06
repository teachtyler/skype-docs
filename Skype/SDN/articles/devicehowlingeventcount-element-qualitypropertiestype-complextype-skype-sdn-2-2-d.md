﻿---
title: DeviceHowlingEventCount element (QualityPropertiesType complexType) 
TOCTitle: DeviceHowlingEventCount element
ms:assetid: 09ee9cad-554d-56de-0498-1bc8b1d63f53
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt149472(v=office.16)
ms:contentKeyID: 65855419
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# DeviceHowlingEventCount element 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Number of times during a session the DeviceHowlingEvent event was fired when audio feedback loop, caused by multiple endpoints sharing the audio path, is detected.


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
<td><p>xs:int</p></td>
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

    <xs:element name="DeviceHowlingEventCount"  type="xs:int">
    
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
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

