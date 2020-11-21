# SoftwareUtil.Steam Class
 

Contains Steam info.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.SoftwareUtil.Steam<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class Steam : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class Steam
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SoftwareUtil.Steam
```

**C++**<br />
``` C++
public ref class Steam sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Steam =  
    class
        inherit AestheticObject
    end
```

The SoftwareUtil.Steam type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_AccountRecoveryUrl">AccountRecoveryUrl</a></td><td>
Gets the official Steam url about regaining access to a lost Steam account, the url is in the same language of the Steam client installed on the current Operating System. 

 Not available for all languages.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_ClientCulture">ClientCulture</a></td><td>
Gets a CultureInfo instance that represents the language of the Steam client installed on the current Operating System.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_ClientFile">ClientFile</a></td><td>
Gets the executable file of the Steam client installed on the current Operating System.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_ClientLanguage">ClientLanguage</a></td><td>
Gets the language of the Steam client installed on the current Operating System.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_InstallDir">InstallDir</a></td><td>
Gets the installation directory of the Steam client installed on the current Operating System.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_IsInstalled">IsInstalled</a></td><td>
Determines whether Steam client is installed in the current Operating System.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_RegistryInstallPath">RegistryInstallPath</a></td><td>
Gets the default Steam registry path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_RegistryUninstallPath">RegistryUninstallPath</a></td><td>
Gets the default Steam Uninstall registry path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_SoftwareUtil_Steam_Version">Version</a></td><td>
Gets the version of the Steam client installed on the current Operating System.</td></tr></table>&nbsp;
<a href="#softwareutil.steam-class">Back to Top</a>

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
<a href="#softwareutil.steam-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />