﻿---
title: IncallEnabled element (ErrorEndPointType complexType) 
TOCTitle: IncallEnabled element (ErrorEndPointType complexType)
ms:assetid: 814ee50f-a076-cf5f-926a-42bf6323999f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt170897(v=office.16)
ms:contentKeyID: 65855472
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# IncallEnabled element 

(ErrorEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Whether the endpoint (Skype for Business client) is capable to send incall quality update messages. This flag does not indicate whether the client is configured to send incall QoE reports.


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

    <xs:element name="IncallEnabled"  type="xs:boolean" minOccurs="0">
    
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
<td><p><a href="endpoint-element-errortype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndPoint</a></p></td>
<td><p><a href="errorendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ErrorEndPointType</a></p></td>
<td><p>Endpoint involved in the ended SIP call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

