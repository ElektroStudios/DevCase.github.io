# FirewallUtil Class
 

Contains Windows Firewall related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.Tools.FirewallUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class FirewallUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class FirewallUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallUtil
```

**C++**<br />
``` C++
public ref class FirewallUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type FirewallUtil =  
    class
        inherit AestheticObject
    end
```

The FirewallUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_Tools_FirewallUtil_FirewallEnabled">FirewallEnabled</a></td><td>
Gets a value indicating whether the Windows Firewall is enabled for the current network profile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_Tools_FirewallUtil_FirewallEnabled_1">FirewallEnabled(FirewallNetworkProfile)</a></td><td>
Gets a value indicating whether the Windows Firewall is enabled for the specified network profile.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_NET_Tools_FirewallUtil_FirewallServiceRunning">FirewallServiceRunning</a></td><td>
Gets a value indicating whether the Windows Firewall service is enabled and running on the current machine. 

 Note that the service could be running but the Firewall itself could be disabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_NET_Tools_FirewallUtil_Rules">Rules</a></td><td>
Gets the current Windows Firewall rules</td></tr></table>&nbsp;
<a href="#firewallutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_AddRule">AddRule</a></td><td>
Asds a rule to Windows firewall.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_Disable">Disable()</a></td><td>
Disables the Windows Firewall for the current network profile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_Disable_1">Disable(FirewallNetworkProfile)</a></td><td>
Disables the Windows Firewall for the specified network profile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_Enable">Enable()</a></td><td>
Enables the Windows Firewall for the current network profile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_Enable_1">Enable(FirewallNetworkProfile)</a></td><td>
Enables the Windows Firewall for the specified network profile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_NET_Tools_FirewallUtil_RemoveRule">RemoveRule</a></td><td>
Removes a rule from Windows firewall.</td></tr></table>&nbsp;
<a href="#firewallutil-class">Back to Top</a>

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
<a href="#firewallutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />