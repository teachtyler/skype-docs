
# startPhoneAudio 


_**Applies to:** Skype for Business 2015_

Initiates a call-via-work. 

## Web Link
<a name="sectionSection0"> </a>

For more on web links, see [Web links](WebLinks.md).



|**Name**|**Description**|
|:-----|:-----|
|rel|The resource that this link points to. In JSON, this is the outer container.|
|href|The location of this resource on the server, and the target of an HTTP operation.|

## Resource description
<a name="sectionSection1"> </a>

startPhoneAudio allows a user to create a new peer-to-peer [conversation](conversation_ref.md) with a [contact](contact_ref.md) using call-via-work. A call-via-work call is an outgoing call that is initiated from a user's phone, and that displays the user's Skype for Business work identity to the remote party. A [phoneAudioInvitation](phoneAudioInvitation_ref.md) will be started; its status can be tracked on the event channel.


### Properties

None


### Links

None


## Operations
<a name="sectionSection2"> </a>




### POST

Starts a [phoneAudioInvitation](phoneAudioInvitation_ref.md) and creates a new conversation with a [contact](contact_ref.md).


#### Query parameters





|**Name**|**Description**|**Required?**|
|:-----|:-----|:-----|
|to|The target of this invitation.|No|

#### Request body

None


#### Response body



|**Item**|**Description**|
|:-----|:-----|
| [phoneAudioInvitation](phoneAudioInvitation_ref.md)|Represents an invitation to a [conversation](conversation_ref.md) for the [phoneAudio](phoneAudio_ref.md) modality.|

#### Synchronous errors

The errors below (if any) are specific to this resource. Generic errors that can apply to any resource are covered in [Generic synchronous errors](GenericSynchronousErrors.md).



|**Error**|**Code**|**Subcode**|**Description**|
|:-----|:-----|:-----|:-----|
|BadRequest|400|NormalizationFailed|The phone normalization failed.|
|Forbidden|403|None|Phone audio is not listed in the capabilities.|
|ServiceFailure|500|CallbackChannelError|The remote event channel is not reachable|
|Conflict|409|AlreadyExists|The already exists error.|
|Conflict|409|TooManyGroups|The too many groups error.|
|Conflict|409|None|Un-supported Service/Resource/API error.|

#### Examples

Only server-supplied query parameters, if any, are shown in the request sample.


#### JSON Request


```

Post https://fe1.contoso.com:443//v1/applications/833/communication/startPhoneAudio HTTP/1.1
Authorization: Bearer cwt=PHNhbWw6QXNzZXJ0aW9uIHhtbG5...uZm8
Host: fe1.contoso.com
Content-Type: application/json
Content-Length: 210
{
"operationId" : "74cb7404e0a247d5a2d4eb0376a47dbf",
"phoneNumber" : "tel:+14255551234",
"importance" : "Normal",
"subject" : "Skype for Business",
"threadId" : "292e0aaef36c426a97757f43dda19d06",
"to" : "sip:john@contoso.com"
}

```


#### JSON Response

This sample is given only as an illustration of response syntax. The semantic content is not guaranteed to correspond to a valid scenario.


```

HTTP/1.1 201 Created
Location: //v1/applications/833/communication/invitations/596


```


#### XML Request


```

Post https://fe1.contoso.com:443//v1/applications/833/communication/startPhoneAudio HTTP/1.1
Authorization: Bearer cwt=PHNhbWw6QXNzZXJ0aW9uIHhtbG5...uZm8
Host: fe1.contoso.com
Content-Type: application/xml
Content-Length: 454
<?xml version="1.0" encoding="utf-8"?>
<input xmlns="http://schemas.microsoft.com/rtc/2012/03/ucwa">
<property name="operationId">74cb7404e0a247d5a2d4eb0376a47dbf</property>
<property name="phoneNumber">tel:+14255551234</property>
<property name="importance">Urgent</property>
<property name="subject">Skype for Business</property>
<property name="threadId">292e0aaef36c426a97757f43dda19d06</property>
<property name="to">sip:john@contoso.com</property>
</input>

```


#### XML Response

This sample is given only as an illustration of response syntax. The semantic content is not guaranteed to correspond to a valid scenario.


```

HTTP/1.1 201 Created
Location: //v1/applications/833/communication/invitations/596


```

