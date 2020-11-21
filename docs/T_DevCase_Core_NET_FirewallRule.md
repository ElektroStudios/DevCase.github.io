# FirewallRule Class
 

Provides the information of a Windows Firewall rule.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.NET.FirewallRule<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("FirewallRule")]
public sealed class FirewallRule : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("FirewallRule")>
Public NotInheritable Class FirewallRule
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FirewallRule
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"FirewallRule")]
public ref class FirewallRule sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("FirewallRule")>]
type FirewallRule =  
    class
        inherit AestheticObject
    end
```

The FirewallRule type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_FirewallRule__ctor">FirewallRule</a></td><td>
Initializes a new instance of the FirewallRule class.</td></tr></table>&nbsp;
<a href="#firewallrule-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Action">Action</a></td><td>
Gets or sets the action for the firewall rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_ApplicationName">ApplicationName</a></td><td>
Gets or sets the friendly name of the application to which the rule applies.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Description">Description</a></td><td>
Gets or sets the description of the rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Direction">Direction</a></td><td>
Gets or sets the direction of traffic to which the rule applies.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_EdgeTraversal">EdgeTraversal</a></td><td>
Gets or sets a value indicating whether edge traversal is enabled or disabled for the rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Enabled">Enabled</a></td><td>
Gets or sets a value indicating whether the rule is enabled.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Grouping">Grouping</a></td><td>
Gets or sets the group to which the rule belongs.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_IcmpTypesAndCodes">IcmpTypesAndCodes</a></td><td>
Gets or sets the list of ICMP types and codes for the rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Interfaces">Interfaces</a></td><td>
Gets or sets the list of interfaces for which the rule applies. 

 The interfaces in the list are represented by their friendly name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_InterfaceTypes">InterfaceTypes</a></td><td>
Gets or sets the list of interface types for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_LocalAddresses">LocalAddresses</a></td><td>
Gets or sets the list of local addresses for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_LocalPorts">LocalPorts</a></td><td>
Gets or sets the list of local ports for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Name">Name</a></td><td>
Gets or sets the friendly name of the rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Profiles">Profiles</a></td><td>
Gets or sets the profiles to which the rule belongs.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_Protocol">Protocol</a></td><td>
Gets or sets IP protocol of the rule.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_RemoteAddresses">RemoteAddresses</a></td><td>
Gets or sets the list of remote addresses for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_RemotePorts">RemotePorts</a></td><td>
Gets or sets the list of remote ports for which the rule applies. 

 If more than one interface type is specified, the strings must be separated by a comma.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_FirewallRule_ServiceName">ServiceName</a></td><td>
Gets or sets the service name property of the application.</td></tr></table>&nbsp;
<a href="#firewallrule-class">Back to Top</a>

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
<a href="#firewallrule-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />