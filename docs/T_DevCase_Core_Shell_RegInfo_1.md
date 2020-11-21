# RegInfo(*T*) Class
 

Defines the info of a registry key of a specific type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.RegInfo(T)<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Core_Shell_RegInfo">DevCase.Core.Shell.RegInfo</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("RegInfo")]
public class RegInfo<T> : AestheticObject

```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("RegInfo")>
Public Class RegInfo(Of T)
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo(Of T)
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"RegInfo")]
generic<typename T>
public ref class RegInfo : public AestheticObject
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("RegInfo")>]
type RegInfo<'T> =  
    class
        inherit AestheticObject
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "T:DevCase.Core.Shell.RegInfo`1"\]</dd></dl>&nbsp;
The RegInfo(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Shell_RegInfo_1__ctor">RegInfo(T)</a></td><td>
Initializes a new instance of the RegInfo(T) class.</td></tr></table>&nbsp;
<a href="#reginfo(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_FullKeyPath">FullKeyPath</a></td><td>
Gets the full key path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_RegistryKey">RegistryKey</a></td><td>
Gets a <a href="P_DevCase_Core_Shell_RegInfo_1_RegistryKey">RegistryKey(RegistryKeyPermissionCheck, RegistryRights)</a> instance of the current RootKey\SubKey.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_RootKeyName">RootKeyName</a></td><td>
Gets or sets the registry root key. ( eg: HKCU or HKEY_CURRENT_USER)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_SubKeyPath">SubKeyPath</a></td><td>
Gets or sets the registry subkey path. ( eg: subkey1\subkey2\ )</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_ValueData">ValueData</a></td><td>
Gets or sets the data of the registry value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_ValueName">ValueName</a></td><td>
Gets or sets the registry value name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_ValueType">ValueType</a></td><td>
Gets or sets the type of the registry value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Shell_RegInfo_1_View">View</a></td><td>
Gets or sets the registry view.</td></tr></table>&nbsp;
<a href="#reginfo(*t*)-class">Back to Top</a>

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
<a href="#reginfo(*t*)-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim regInfoByte As New RegInfo(Of Byte())
With regInfoByte
    .RootKeyName = "HKCU"
    .SubKeyPath = "Subkey Path"
    .ValueName = "Value Name"
    .ValueType = Microsoft.Win32.RegistryValueKind.Binary
    .ValueData = Global.System.Text.Encoding.ASCII.GetBytes("Hello World!")
End With
```


## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />