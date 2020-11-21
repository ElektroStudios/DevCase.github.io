# NetworkUtil Class
 

Contains networking related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Tools.NetworkUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class NetworkUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class NetworkUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkUtil
```

**C++**<br />
``` C++
public ref class NetworkUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type NetworkUtil =  
    class
        inherit AestheticObject
    end
```

The NetworkUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_Tools_NetworkUtil_IsNetworkAvailable">IsNetworkAvailable</a></td><td>
Gets a value indicating whether at least one of the current network adapters is capable of connecting to Internet.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_Tools_NetworkUtil_NetworkInterfaceNames">NetworkInterfaceNames</a></td><td>
Gets the current network interface names.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_NET_Tools_NetworkUtil_TcpConnctions">TcpConnctions</a></td><td>
Gets the active TCP connctions.</td></tr></table>&nbsp;
<a href="#networkutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_GenerateRandomIpv4">GenerateRandomIpv4</a></td><td>
Generates a random IPv4 value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_GetPublicIP">GetPublicIP</a></td><td>
Gets the public IP address of the current machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_HostnameToIp">HostnameToIp</a></td><td>
Gets the IP addresses that are associated to a hostname.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_IpToHostName">IpToHostName</a></td><td>
Gets the hostname that is associated to the specified IP address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_Ping">Ping</a></td><td>
Pings the specified address or hostname to determine whether a remote computer is accessible over the network.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_PortScan">PortScan</a></td><td>
Scans for a open port on the specified IP address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_PortScanRange">PortScanRange</a></td><td>
Scans for open ports in a range of port numbers on the specified IP address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_NetworkUtil_ValidateIp">ValidateIp</a></td><td>
Validates a IP address.</td></tr></table>&nbsp;
<a href="#networkutil-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Core_NET_Tools_NetworkUtil_NetworkStatusChanged">NetworkStatusChanged</a></td><td>
Occurs when the state of Internet connectivity changes.</td></tr></table>&nbsp;
<a href="#networkutil-class">Back to Top</a>

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
<a href="#networkutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />