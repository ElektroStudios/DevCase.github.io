# GmailClient Class
 

A client for Gmail services.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.Gmail.GmailClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GmailClient : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class GmailClient
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
```

**C++**<br />
``` C++
public ref class GmailClient sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GmailClient =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The GmailClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient__ctor">GmailClient(String, MailAddress, GmailScopes)</a></td><td>
Initializes a new instance of the GmailClient class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient__ctor_1">GmailClient(String, String, GmailScopes)</a></td><td>
Initializes a new instance of the GmailClient class.</td></tr></table>&nbsp;
<a href="#gmailclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Gmail_GmailClient_IsAuthorized">IsAuthorized</a></td><td>
Gets a value that determines whether Gmail API authorization was done.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Gmail_GmailClient_MailAddress">MailAddress</a></td><td>
Gets the mail address to authorize Gmail service. (e.g: "yourmail@gmail.com")</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Gmail_GmailClient_Scope">Scope</a></td><td>
Gets the current Gmail OAuthv2 scopes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_Gmail_GmailClient_Secrets">Secrets</a></td><td>
Gets the client credentials.</td></tr></table>&nbsp;
<a href="#gmailclient-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_Authorize">Authorize</a></td><td>
Authorizes this instance to use GMail API services.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_AuthorizeAsync">AuthorizeAsync</a></td><td>
Authorizes this instance to use Gmail API services.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_DeleteMessage">DeleteMessage</a></td><td>
Permanentlly deletes the specified message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_DeleteMessageAsync">DeleteMessageAsync</a></td><td>
Asynchronously permanentlly deletes the specified message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderAsyncByDisplayName">GetFolderAsyncByDisplayName</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified display name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderAsyncById">GetFolderAsyncById</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderAsyncByKnownId">GetFolderAsyncByKnownId</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified known Id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderByDisplayName">GetFolderByDisplayName</a></td><td>
Gets a mailbox folder that satisfies the specified display name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderById">GetFolderById</a></td><td>
Gets a mailbox folder that satisfies the specified id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetFolderByKnownId">GetFolderByKnownId</a></td><td>
Gets a mailbox folder that satisfies the specified known Id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetMessages">GetMessages</a></td><td>
Gets the messages contained in the specified mailbox folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_GetMessagesAsync">GetMessagesAsync</a></td><td>
Asynchronously gets the messages contained in the specified mailbox folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_RecycleMessage">RecycleMessage</a></td><td>
Sends the specified message to the `Trash` folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_RecycleMessageAsync">RecycleMessageAsync</a></td><td>
Asynchronously sends the specified message to the `Trash` folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml">SendMessageHtml(String, String, MailAddress)</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_3">SendMessageHtml(String, String, MailAddressCollection)</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_6">SendMessageHtml(String, String, String)</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_9">SendMessageHtml(String, String, String[])</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_1">SendMessageHtml(String, String, MailAddress, ICollection(Attachment))</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_2">SendMessageHtml(String, String, MailAddress, Attachment[])</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_4">SendMessageHtml(String, String, MailAddressCollection, ICollection(Attachment))</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_5">SendMessageHtml(String, String, MailAddressCollection, Attachment[])</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_7">SendMessageHtml(String, String, String, ICollection(Attachment))</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_8">SendMessageHtml(String, String, String, Attachment[])</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_10">SendMessageHtml(String, String, String[], ICollection(Attachment))</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml_11">SendMessageHtml(String, String, String[], Attachment[])</a></td><td>
Sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync">SendMessageHtmlAsync(String, String, MailAddress)</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_3">SendMessageHtmlAsync(String, String, MailAddressCollection)</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_6">SendMessageHtmlAsync(String, String, String)</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_9">SendMessageHtmlAsync(String, String, String[])</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_1">SendMessageHtmlAsync(String, String, MailAddress, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_2">SendMessageHtmlAsync(String, String, MailAddress, Attachment[])</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_4">SendMessageHtmlAsync(String, String, MailAddressCollection, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_5">SendMessageHtmlAsync(String, String, MailAddressCollection, Attachment[])</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_7">SendMessageHtmlAsync(String, String, String, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_8">SendMessageHtmlAsync(String, String, String, Attachment[])</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_10">SendMessageHtmlAsync(String, String, String[], ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync_11">SendMessageHtmlAsync(String, String, String[], Attachment[])</a></td><td>
Asynchronously sends a mail with a HTML body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText">SendMessageText(String, String, MailAddress)</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_3">SendMessageText(String, String, MailAddressCollection)</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_6">SendMessageText(String, String, String)</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_9">SendMessageText(String, String, String[])</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_1">SendMessageText(String, String, MailAddress, ICollection(Attachment))</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_2">SendMessageText(String, String, MailAddress, Attachment[])</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_4">SendMessageText(String, String, MailAddressCollection, ICollection(Attachment))</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_5">SendMessageText(String, String, MailAddressCollection, Attachment[])</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_7">SendMessageText(String, String, String, ICollection(Attachment))</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_8">SendMessageText(String, String, String, Attachment[])</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_10">SendMessageText(String, String, String[], ICollection(Attachment))</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageText_11">SendMessageText(String, String, String[], Attachment[])</a></td><td>
Sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync">SendMessageTextAsync(String, String, MailAddress)</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_3">SendMessageTextAsync(String, String, MailAddressCollection)</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_6">SendMessageTextAsync(String, String, String)</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_9">SendMessageTextAsync(String, String, String[])</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_1">SendMessageTextAsync(String, String, MailAddress, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_2">SendMessageTextAsync(String, String, MailAddress, Attachment[])</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_4">SendMessageTextAsync(String, String, MailAddressCollection, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_5">SendMessageTextAsync(String, String, MailAddressCollection, Attachment[])</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_7">SendMessageTextAsync(String, String, String, ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_8">SendMessageTextAsync(String, String, String, Attachment[])</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_10">SendMessageTextAsync(String, String, String[], ICollection(Attachment))</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync_11">SendMessageTextAsync(String, String, String[], Attachment[])</a></td><td>
Asynchronously sends a mail with a plain text body.</td></tr></table>&nbsp;
<a href="#gmailclient-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#gmailclient-class">Back to Top</a>

## Examples
This example demonstrates how to iterate the messages contained in the "Inbox" mailbox folder to retrieve message info. 
**VB**<br />
``` VB
Imports Google.Apis.Auth.OAuth2
Imports Google.Apis.Gmail.v1.Data

Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim folder As Google.Apis.Gmail.v1.Data.Label = Await client.GetFolderAsyncByKnownId(GmailFolderIds.Inbox)
Dim messages As List(Of Google.Apis.Gmail.v1.Data.Message) = Await client.GetMessagesAsync(folder)
Dim msgCount As Integer

Dim [date] As String = ""
Dim from As String = ""
Dim subject As String = ""
Dim body As String = ""

For Each msg As Google.Apis.Gmail.v1.Data.Message In messages

    For Each header As MessagePartHeader In msg.Payload.Headers

        Select Case header.Name

            Case "Date"
                [date] = header.Value

            Case "From"
                from = header.Value

            Case "Subject"
                subject = header.Value

            Case Else
                ' ...

        End Select

    Next header

    Console.WriteLine(String.Format("Count: {0}; Id: {1}; From: {2}, Date: {3}, Subject: {4}",
                                    Interlocked.Increment(msgCount),
                                    msg.Id, from, [date], subject))

    body = msg.Payload.Body.Data

    ' We need to evaluate this because some message bodies are Base64 encoded, and some others aren't.
    If DevCase.Core.Cryptography.CryptoUtil.IsBase64Encoded(msg.Payload.Body.Data) Then
        body = DevCase.Core.Cryptography.CryptoUtil.Base64Decode(msg.Payload.Body.Data)
    End If

    ' Console.WriteLine(body)

Next msg
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />