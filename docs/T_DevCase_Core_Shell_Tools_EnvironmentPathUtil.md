# EnvironmentPathUtil Class
 

Contains Windows `PATH` and `PATHEXT` environment variables related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.EnvironmentPathUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class EnvironmentPathUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class EnvironmentPathUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As EnvironmentPathUtil
```

**C++**<br />
``` C++
public ref class EnvironmentPathUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type EnvironmentPathUtil =  
    class
        inherit AestheticObject
    end
```

The EnvironmentPathUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_DefaultPathExt">DefaultPathExt</a></td><td>
Gets the default data of the PATHEXt registry value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_DefaultPathWin32">DefaultPathWin32</a></td><td>
Gets the default data of the PATH registry value for a 32-Bit Windows.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_DefaultPathWin64">DefaultPathWin64</a></td><td>
Gets the default data of the PATH registry value for a 64-Bit Windows.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_EnvironmentPathCurrentUser">EnvironmentPathCurrentUser</a></td><td>
Gets the registry path of the Environment subkey for the current user.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_EnvironmentPathMachine">EnvironmentPathMachine</a></td><td>
Gets the registry path of the Environment subkey for all users.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_PathData">PathData</a></td><td>
Gets the data of the `PATH` registry value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_EnvironmentPathUtil_PathExtData">PathExtData</a></td><td>
Gets the data of the `PATHEXT` registry value.</td></tr></table>&nbsp;
<a href="#environmentpathutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_AddDirectory">AddDirectory</a></td><td>
Adds a directory into the `PATH` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_AddExtension">AddExtension</a></td><td>
Adds a file extension into the `PATHEXT` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_ContainsDirectory">ContainsDirectory</a></td><td>
Determines whether the `PATH` registry value contains the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_ContainsExtension">ContainsExtension</a></td><td>
Determines whether the `PATHEXT` registry value contains the specified file extension.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_CreatePath">CreatePath</a></td><td>
Creates an empty `PATH` value in the registry. 

 Optionally fills the value with the specified data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_CreatePathExt">CreatePathExt</a></td><td>
Creates an empty `PATHEXT` value in the registry. 

 Optionally fills the value with the specified data.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_Export">Export</a></td><td>
Exports the `PATH` and `PATHEXT` values to a target registry file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_GetDefaultPathData">GetDefaultPathData</a></td><td>
Gets the default data of the `PATH` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_GetPathData">GetPathData</a></td><td>
Gets the data of the `PATH` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_GetPathExtData">GetPathExtData</a></td><td>
Gets data of the data of the `PATHEXT` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_PathExists">PathExists</a></td><td>
Determines whether the `PATH` value exists in the registry.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_PathExtExists">PathExtExists</a></td><td>
Determines whether the `PATHEXT` value exists on the registry of the specified user.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveDirectory">RemoveDirectory(RegistryScope, Int32)</a></td><td>
Removes a directory from the `PATH` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveDirectory_1">RemoveDirectory(RegistryScope, String)</a></td><td>
Removes a directory from the `PATH` registry value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveExtension">RemoveExtension(RegistryScope, Int32)</a></td><td>
Removes a file extension from the PATHEXT registry value of the specified user.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveExtension_1">RemoveExtension(RegistryScope, String)</a></td><td>
Removes a file extension from the `PATHEXT` registry value of the specified user.</td></tr></table>&nbsp;
<a href="#environmentpathutil-class">Back to Top</a>

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
<a href="#environmentpathutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />