# DevWebClient Class
 

A extended WebClient component, with support for cookies and requests timeout.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Net.WebClient<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.DevWebClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Component), "Component.bmp")]
[ComVisibleAttribute(true)]
public class DevWebClient : WebClient
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Component), "Component.bmp")>
<ComVisibleAttribute(true)>
Public Class DevWebClient
	Inherits WebClient
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebClient
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Component), L"Component.bmp")]
[ComVisibleAttribute(true)]
public ref class DevWebClient : public WebClient
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Component), "Component.bmp")>]
[<ComVisibleAttribute(true)>]
type DevWebClient =  
    class
        inherit WebClient
    end
```

The DevWebClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_DevWebClient__ctor">DevWebClient</a></td><td>
Initializes a new instance of the DevWebClient class.</td></tr></table>&nbsp;
<a href="#devwebclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_DevWebClient_CookieContainer">CookieContainer</a></td><td>
Gets or sets the cookies associated with this DevWebClient.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_DevWebClient_CookiesEnabled">CookiesEnabled</a></td><td>
Gets or sets a value indicating whether cookies are enabled. 

 Default value is `false` (`False` in Visual Basic).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_DevWebClient_RequestTimeout">RequestTimeout</a></td><td>
Gets or sets the time interval, in milliseconds, until the requests made by this DevWebClient times out.</td></tr></table>&nbsp;
<a href="#devwebclient-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devwebclient-class">Back to Top</a>

## Remarks
Original idea taken from: http://www.codingvision.net/tips-and-tricks/c-webclient-with-cookies

## Examples
This is a code example that demonstrates how to login to a website. 
**VB**<br />
``` VB
Dim uri As New Uri("https://foro.elhacker.net/index.php?action=login2", UriKind.Absolute)
Dim cred As New NetworkCredential("USERNAME", "PASSWORD")
Dim query As String = HttpUtility.ParseQueryString($"cookielength=90&user={cred.UserName}&passwrd={cred.Password}").ToString()

Using client As New DevWebClient() With {.CookiesEnabled = True}
    client.Headers.Add(HttpRequestHeader.ContentType, "application/x-www-form-urlencoded")

    Dim response As String = client.UploadString(uri, "POST", query)
    Console.WriteLine(response)

    Dim cookies As CookieCollection = client.CookieContainer.GetCookies(uri)
    For Each cookie As Cookie In cookies
        Console.WriteLine("{0}: {1}", cookie.Name, cookie.Value)
    Next
End Using
```


## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />