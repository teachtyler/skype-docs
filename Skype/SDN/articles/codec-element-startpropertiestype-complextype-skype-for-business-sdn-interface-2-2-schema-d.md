﻿---
title: Codec element (StartPropertiesType complexType) 
TOCTitle: Codec element (StartPropertiesType complexType)
ms:assetid: 03e6b33a-5f2d-eb7b-8dda-6652d86dd62a
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt149446(v=office.16)
ms:contentKeyID: 65855393
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Codec element 

(StartPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Codec and estimates for the bandwidth that the codecs will use. This list contains all codecs that are agreed upon by the two endpoints. Both end-points may decide to switch among these codecs at any time (without additional signalling).


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
<td><p><a href="codectype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">CodecType</a></p></td>
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

    <xs:element name="Codec"  type="CodecType" maxOccurs="unbounded" minOccurs="0">
    
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
<td><p><a href="properties-element-startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">StartPropertiesType</a></p></td>
<td><p>Properties of the started or updated media stream.</p></td>
</tr>
</tbody>
</table>


### Child elements

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
<td><p><a href="bandwidth-element-codectype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Bandwidth</a></p></td>
<td><p><a href="bandwidthdatatype-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">BandwidthDataType</a></p></td>
<td><p>Average estimated bandwidth.</p></td>
</tr>
<tr class="even">
<td><p><a href="maxbandwidth-element-codectype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MaxBandwidth</a></p></td>
<td><p><a href="bandwidthdatatype-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">BandwidthDataType</a></p></td>
<td><p>Upper limit of the estimated bandwidth.</p></td>
</tr>
</tbody>
</table>


### Attributes

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Type</p></th>
<th><p>Required</p></th>
<th><p>Description</p></th>
<th><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name</p></td>
<td><p>xs:string</p></td>
<td><p>required</p></td>
<td><p>Name of the standard SIP codec used for the media stream.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
<tr class="even">
<td><p>PayLoadType</p></td>
<td><p>xs:int</p></td>
<td><p>optional</p></td>
<td><p>Payload type used when this codec is active.</p></td>
<td><p>Values of the xs:int type.</p></td>
</tr>
</tbody>
</table>

