# UrlShortenerClient Class
 

A client for Google's Url Shortener service.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Google.UrlShortener.UrlShortenerClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class UrlShortenerClient : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class UrlShortenerClient
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As UrlShortenerClient
```

**C++**<br />
``` C++
public ref class UrlShortenerClient sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type UrlShortenerClient =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The UrlShortenerClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient__ctor">UrlShortenerClient</a></td><td>
Initializes a new instance of the UrlShortenerClient class.</td></tr></table>&nbsp;
<a href="#urlshortenerclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ApiKey">ApiKey</a></td><td>
Gets the API key to use UrlShortener service. 

 You can get an API key at Google's API Console: <a href="http://console.developers.google.com/apis" target="_blank">http://console.developers.google.com/apis</a></td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_IsAuthorized">IsAuthorized</a></td><td>
Gets a value that determines whether UrlShortener API authorization was done.</td></tr></table>&nbsp;
<a href="#urlshortenerclient-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Authorize">Authorize</a></td><td>
Authorizes this instance to use UrlShortener API service.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_AuthorizeAsync">AuthorizeAsync</a></td><td>
Asynchronously authorizes this instance to use UrlShortener API service.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Resolve">Resolve(String)</a></td><td>
Resolves a shortened Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Resolve_1">Resolve(Uri)</a></td><td>
Resolves a shortened Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ResolveAsync">ResolveAsync(String)</a></td><td>
Asynchronously resolves a shortened Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ResolveAsync_1">ResolveAsync(Uri)</a></td><td>
Asynchronously resolves a shortened Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Shorten">Shorten(String)</a></td><td>
Shortens the specified Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_Shorten_1">Shorten(Uri)</a></td><td>
Shortens the specified Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ShortenAsync">ShortenAsync(String)</a></td><td>
Asynchronously shortens the specified Url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Google_UrlShortener_UrlShortenerClient_ShortenAsync_1">ShortenAsync(Uri)</a></td><td>
Asynchronously shortens the specified Url.</td></tr></table>&nbsp;
<a href="#urlshortenerclient-class">Back to Top</a>

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
<a href="#urlshortenerclient-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to shorten a Url. 
**VB**<br />
``` VB
Dim client As New UrlShortenerClient("YOUR API KEY")
Dim authSuccess As Boolean = Await client.AuthorizeAsync()
Dim sourceUrl As String = "https://msdn.microsoft.com/"
Dim shortenedUrl As String = Await client.ShortenAsync(sourceUrl)
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_UrlShortener">DevCase.ThirdParty.Google.UrlShortener Namespace</a><br />