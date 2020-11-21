# SmtpClients Class
 

Represents the Bitcoin (symbol: BTC) cryptocurrency.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.NET.SmtpClients<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SmtpClients
```

**VB**<br />
``` VB
Public NotInheritable Class SmtpClients
```

**VB Usage**<br />
``` VB Usage
Dim instance As SmtpClients
```

**C++**<br />
``` C++
public ref class SmtpClients sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SmtpClients =  class end
```

The SmtpClients type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_SmtpClients__ctor">SmtpClients</a></td><td>
Initializes a new instance of the SmtpClients class.</td></tr></table>&nbsp;
<a href="#smtpclients-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_GoogleMailSmtpClient">GoogleMailSmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Google Gmail SMTP server. 

 Login webpage: <a href="https://accounts.google.com/servicelogin/" target="_blank">https://accounts.google.com/servicelogin/</a>

 Note that in order to send SMTP e-mails, you must enable application access for your GMail account by following the next url: 

<a href="http://www.google.com/settings/security/lesssecureapps" target="_blank">http://www.google.com/settings/security/lesssecureapps</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_MailRuSmtpClient">MailRuSmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Mail.ru SMTP server. 

 Login webpage: <a href="https://e.mail.ru/cgi-bin/login?lang=en_US" target="_blank">https://e.mail.ru/cgi-bin/login?lang=en_US</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_MicrosoftLiveSmtpClient">MicrosoftLiveSmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Microsoft Live SMTP server. 

 Login webpage: <a href="https://outlook.live.com/" target="_blank">https://outlook.live.com/</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_MicrosoftOffice365SmtpClient">MicrosoftOffice365SmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Microsoft Office-365 SMTP server. 

 Login webpage: <a href="https://login.microsoftonline.com/" target="_blank">https://login.microsoftonline.com/</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_YandexInternationalSmtpClient">YandexInternationalSmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Yandex.com SMTP server. 

 Login webpage: <a href="https://mail.yandex.com/" target="_blank">https://mail.yandex.com/</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_SmtpClients_YandexRussianSmtpClient">YandexRussianSmtpClient</a></td><td>
Gets a value that represents the SMTP client which allows applications to send e-mails through Yandex.ru SMTP server. 

 Login webpage: <a href="https://mail.yandex.ru/" target="_blank">https://mail.yandex.ru/</a></td></tr></table>&nbsp;
<a href="#smtpclients-class">Back to Top</a>

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
<a href="#smtpclients-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />