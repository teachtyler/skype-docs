﻿---
title: ByeEndPointType complexType 
TOCTitle: ByeEndPointType complexType
ms:assetid: 892cbcd0-404e-7f77-aa63-b64437ccbefa
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171055(v=office.16)
ms:contentKeyID: 65855629
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ByeEndPointType complexType 

(Skype for Business SDN Interface 2.2, Schema "D")


**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="ByeEndPointType">
      </xs:complexType>
      
```

## Elements and attributes

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
<td><p><a href="contact-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Contact</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user as extracted from the Contact header of the underlying SIP message. This field is obfuscated unless hidepii is set to false in the Dialog Listener configuration file.</p></td>
</tr>
<tr class="even">
<td><p><a href="epid-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EPId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Endpoint Id of the endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="eptype-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EPType</a></p></td>
<td><p>xs:string</p></td>
<td><p>Indicates that this endpoint is of the Skype for Business Room System type or not.</p></td>
</tr>
<tr class="even">
<td><p><a href="hostip-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">HostIP</a></p></td>
<td><p>xs:string</p></td>
<td><p>IP address of the endpoint's host in the local network.</p></td>
</tr>
<tr class="odd">
<td><p><a href="hostport-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">HostPort</a></p></td>
<td><p>xs:string</p></td>
<td><p>Port used on the endpoint's host.</p></td>
</tr>
<tr class="even">
<td><p><a href="id-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Id</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier of the endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="incallenabled-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">IncallEnabled</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>Whether the endpoint (Skype for Business client) is capable to send incall quality update messages. This flag does not indicate whether the client is configured to send incall QoE reports.</p></td>
</tr>
<tr class="even">
<td><p><a href="ip-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">IP</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP address of the the media stream source or destination.</p></td>
</tr>
<tr class="odd">
<td><p><a href="pai-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">PAI</a></p></td>
<td><p>xs:string</p></td>
<td><p>P-ASSERTED Identity.</p></td>
</tr>
<tr class="even">
<td><p><a href="port-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Port</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port number of the destination or source of the media stream used by this endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="reflexiveip-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ReflexiveIP</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP used outside of the NAT.</p></td>
</tr>
<tr class="even">
<td><p><a href="reflexiveport-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ReflexivePort</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port useed on the NAT.</p></td>
</tr>
<tr class="odd">
<td><p><a href="relay-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Relay</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP Address of the first relay used in the media traffic.</p></td>
</tr>
<tr class="even">
<td><p><a href="relayport-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">RelayPort</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port number of the relay.</p></td>
</tr>
<tr class="odd">
<td><p><a href="tenantid-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">TenantId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier for the tenanat that this endpoing belongs to.</p></td>
</tr>
<tr class="even">
<td><p><a href="trunk-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Trunk</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier for the SipTrunk or other SIP device used to connect to the endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="uri-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">URI</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user signed in via the endpoint as extracted from the SIP header.. This field is obfuscated unless hidepii is set to false in the Dialog Listener configuration file.</p></td>
</tr>
<tr class="even">
<td><p><a href="useragent-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">UserAgent</a></p></td>
<td><p><a href="useragenttype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">UserAgentType</a></p></td>
<td><p>Skype for Business client name and version.</p></td>
</tr>
<tr class="odd">
<td><p><a href="wireless-element-byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Wireless</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>Flag indicating if the endpoint is using a wireless network.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

