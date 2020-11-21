# GeckoFxUtil Class
 

Contains GeckoFx related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.GeckoFx.GeckoFxUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class GeckoFxUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class GeckoFxUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GeckoFxUtil
```

**C++**<br />
``` C++
public ref class GeckoFxUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type GeckoFxUtil =  
    class
        inherit AestheticObject
    end
```

The GeckoFxUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_BackoffCount">BackoffCount</a></td><td>
Gets or sets the maximum number of times the content of a webpage will do timer-based reflows. 

 Rather than wait until a page has completely downloaded to display it to the user, Mozilla applications will periodically render what has been received to that point. 

 Because reflowing the page every time additional data is received greatly slows down total page load time, a timer was added so that the page would not reflow too often. 

 After this number has been reached, the page will only reflow once it is finished downloading.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_DefaultHttpProxy">DefaultHttpProxy</a></td><td>
Gets or sets the default HTTP proxy for GeckoFx web-browsers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_DefaultProxyType">DefaultProxyType</a></td><td>
Gets or sets the default proxy type for GeckoFx web-browsers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_DefaultSslProxy">DefaultSslProxy</a></td><td>
Gets or sets the default SSL proxy for GeckoFx web-browsers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_ExposePluginFullPath">ExposePluginFullPath</a></td><td>
Gets or sets a value indicating whether to expose the full path of a installed plugin file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_ExtensionBlocklistEnabled">ExtensionBlocklistEnabled</a></td><td>
Gets or sets a value that determines wheter to retrieve a blocklist to restrict extension installation. 

 Mozilla applications will periodically retrieve a blocklist from the server specified in extensions.blocklist.url. 

 While Mozilla 's add-on system is a powerful feature, it can also be a vector for malware. 

 Specific extensions can be blocklisted from a central server (by default, addons.mozilla.org).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_InitialPaintDelay">InitialPaintDelay</a></td><td>
Gets or sets the amont of milliseconds to wait before first displaying the page. 

 Using keep-alive connections improves performance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_MaxConnectionsPerServer">MaxConnectionsPerServer</a></td><td>
Gets or sets the maximum amount of HTTP connections the application can make to a single server.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_MaxPersistentConnectionsPerServer">MaxPersistentConnectionsPerServer</a></td><td>
Gets or sets the maximum amount of HTTP keep-alive connections the application can have open at once to a single server. 

 Using keep-alive connections improves performance.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_PipeliningEnabled">PipeliningEnabled</a></td><td>
Gets or sets a value indicating whether HTTP pipelining is enabled. 



 Pipelining reduces network load and can reduce page loading times over high-latency connections, but not all servers support it. 

 Some servers may even behave incorrectly if they receive pipelined requests. 

 If a proxy server is not configured, this preference controls whether to attempt to use pipelining.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_PipeliningMaxRequests">PipeliningMaxRequests</a></td><td>
Gets or sets the maximum amount of requests to pipeline at once when pipelining is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_ProxyPipeliningEnabled">ProxyPipeliningEnabled</a></td><td>
Gets or sets a value indicating whether HTTP pipelining is enabled in proxy servers.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_SessionHistoryMaxEntries">SessionHistoryMaxEntries</a></td><td>
Gets or sets the maximum amount of pages in the browser's session history.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_SessionHistoryMaxViewers">SessionHistoryMaxViewers</a></td><td>
Gets or sets the maximum amount of pages that can be stored in memory. 

 Pages that were recently visited are stored in memory in such a way that they don't have to be re-parsed (this is different from the memory cache). 

 This improves performance when pressing `Back` and `Forward` buttons.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_SslPipeliningEnabled">SslPipeliningEnabled</a></td><td>
Gets or sets a value indicating whether HTTP with SSL pipelining is enabled. 



 Many problems with pipelining are related to broken proxy servers sitting between the user and the destination web site. 

 Since this is not a problem with SSL, it is possible to turn on pipelining for SSL websites only. 

 This preference controls whether to use pipelining for secure websites, regardless of network.http.pipelining.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_SubmenuDelay">SubmenuDelay</a></td><td>
Gets or sets the delay, in milliseconds, between hovering over a menu option with a submenu and the submenu appearing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_TrimOnMinimize">TrimOnMinimize</a></td><td>
Gets or sets a value that determines whether to mark memory as preferably swappable, from a minimized Mozilla Windows application. 

 When a program is minimized and left for a period of time, Windows will swap memory the program is using from RAM onto the hard disk in anticipation that other programs might need RAM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_XulErrorPagesEnabled">XulErrorPagesEnabled</a></td><td>
Gets or sets a value that determines wheter xul error pages are enabled. 

 If xul error pages are disabled, the alert dialogue does not provide any means to override/ignore the error. 

 If xul error pages are enabld, you are given the option to override the error and walked through the process quite nicely.</td></tr></table>&nbsp;
<a href="#geckofxutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_GeckoFx_GeckoFxUtil_RemoveAllCookies">RemoveAllCookies</a></td><td>
Removes all the cookies that has been accumulated by GeckoFx web-browsers.</td></tr></table>&nbsp;
<a href="#geckofxutil-class">Back to Top</a>

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
<a href="#geckofxutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />