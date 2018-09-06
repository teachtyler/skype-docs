﻿---
title: QualityEndPointType complexType 
TOCTitle: QualityEndPointType complexType
ms:assetid: f61c1680-de97-b31f-b804-b8dce4956f29
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Mt171069(v=office.16)
ms:contentKeyID: 65855642
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# QualityEndPointType complexType 

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
      <xs:complexType name="QualityEndPointType">
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
<td><p><a href="bssid-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">BSSID</a></p></td>
<td><p><a href="bssidpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">BSSIDPattern</a></p></td>
<td><p>Id of an access point for a WiFi/wireless connection.</p></td>
</tr>
<tr class="even">
<td><p><a href="connection-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">Connection</a></p></td>
<td><p><a href="connectionplatforms-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ConnectionPlatforms</a></p></td>
<td><p>Connection type such as &quot;wired&quot; or &quot;wireless&quot;.</p></td>
</tr>
<tr class="odd">
<td><p><a href="contact-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Contact</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user as extracted from the Contact header of the underlying SIP message. This field is obfuscated unless hidepii is set to false in the DialogListener configuration file.</p></td>
</tr>
<tr class="even">
<td><p><a href="cpuname-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">CPUName</a></p></td>
<td><p>xs:string</p></td>
<td><p>Name of the CPU.</p></td>
</tr>
<tr class="odd">
<td><p><a href="cpunumberofcores-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">CPUNumberOfCores</a></p></td>
<td><p>xs:int</p></td>
<td><p>Number of CPU cores in the endpoint device.</p></td>
</tr>
<tr class="even">
<td><p><a href="cpuprocessorspeed-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">CPUProcessorSpeed</a></p></td>
<td><p>xs:string</p></td>
<td><p>Processor speed rating.</p></td>
</tr>
<tr class="odd">
<td><p><a href="dscpinbound-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">DSCPInbound</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>QoS category marking when the stream is received on this endpoint. This field is populated only from Skype for Business clients newer than Skype for Business 2013.</p></td>
</tr>
<tr class="even">
<td><p><a href="dscpoutbound-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">DSCPOutbound</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>QoS category marking used on send the stream from this endpoint. This field is populated only from Skype for Business clients newer than Skype for Business 2013.</p></td>
</tr>
<tr class="odd">
<td><p><a href="epid-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EPId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Endpoint Id of the endpoint.</p></td>
</tr>
<tr class="even">
<td><p><a href="eptype-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EPType</a></p></td>
<td><p>xs:string</p></td>
<td><p>Indicates that this endpoint is of the Skype for Business Room System type or not.</p></td>
</tr>
<tr class="odd">
<td><p><a href="hostip-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">HostIP</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP address of the the media stream source or destination.</p></td>
</tr>
<tr class="even">
<td><p><a href="hostport-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">HostPort</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port number of the destination or source of the media stream used by this endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="id-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Id</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier of the endpoint.</p></td>
</tr>
<tr class="even">
<td><p><a href="inside-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Inside</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>(Deprecated - since Skype for Business 2013, this field is not reliable anymore.) Indicates if the source is registered within the enterprise (True) or not (False).</p></td>
</tr>
<tr class="odd">
<td><p><a href="ip-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">IP</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP address of the the media stream source or destination.</p></td>
</tr>
<tr class="even">
<td><p><a href="linkspeed-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">LinkSpeed</a></p></td>
<td><p>xs:double</p></td>
<td><p>Basic bandwidth of the connection.</p></td>
</tr>
<tr class="odd">
<td><p><a href="macaddr-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MACAddr</a></p></td>
<td><p>xs:string</p></td>
<td><p>MAC address of the endpoint.</p></td>
</tr>
<tr class="even">
<td><p><a href="os-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">OS</a></p></td>
<td><p>xs:string</p></td>
<td><p>Operating System used on the endpoint device.</p></td>
</tr>
<tr class="odd">
<td><p><a href="pai-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">PAI</a></p></td>
<td><p>xs:string</p></td>
<td><p>P-Asserted Identity.</p></td>
</tr>
<tr class="even">
<td><p><a href="port-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Port</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port number of the destination or source of the media stream used by this endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="reflexiveip-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">ReflexiveIP</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP used outside of the NAT.</p></td>
</tr>
<tr class="even">
<td><p><a href="reflexiveport-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">ReflexivePort</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port used on the NAT.</p></td>
</tr>
<tr class="odd">
<td><p><a href="relay-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Relay</a></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
<td><p>IP Address of the first relay used in the media traffic.</p></td>
</tr>
<tr class="even">
<td><p><a href="relayport-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">RelayPort</a></p></td>
<td><p><a href="portpattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">PortPattern</a></p></td>
<td><p>Port number of the relay.</p></td>
</tr>
<tr class="odd">
<td><p><a href="trunk-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Trunk</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier for the SipTrunk or other SIP device used to connect to the endpoint.</p></td>
</tr>
<tr class="even">
<td><p><a href="uri-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">URI</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user signed in via the endpoint as extracted from the SIP header.. This field is obfuscated unless hidepii is set to false in the DialogListener configuration file.</p></td>
</tr>
<tr class="odd">
<td><p><a href="useragent-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">UserAgent</a></p></td>
<td><p><a href="useragenttype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">UserAgentType</a></p></td>
<td><p>Skype for Business client and version.</p></td>
</tr>
<tr class="even">
<td><p><a href="virtualization-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">Virtualization</a></p></td>
<td><p>xs:string</p></td>
<td><p>Type of virtualization used.</p></td>
</tr>
<tr class="odd">
<td><p><a href="vpn-element-qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">VPN</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>Indicates if the user is on VPN (True) or not (False).</p></td>
</tr>
<tr class="even">
<td><p><a href="wifidriverdevicedesc-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">WifiDriverDeviceDesc</a></p></td>
<td><p>xs:string</p></td>
<td><p>Wifi Driver Device description.</p></td>
</tr>
<tr class="odd">
<td><p><a href="wifidriverversion-element-qualityendpointtype-complextype-skype-sdn-2-2-d.md">WifiDriverVersion</a></p></td>
<td><p>xs:string</p></td>
<td><p>Wifi Driver Version.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

