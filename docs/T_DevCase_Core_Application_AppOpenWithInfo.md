# AppOpenWithInfo Class
 

Represents the `OpenWith` specific information for an application registration through `HKEY_CLASSES_ROOT\Applications\ApplicationName.exe` registry subkey.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.AppOpenWithInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class AppOpenWithInfo : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class AppOpenWithInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppOpenWithInfo
```

**C++**<br />
``` C++
public ref class AppOpenWithInfo sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type AppOpenWithInfo =  
    class
        inherit AestheticObject
    end
```

The AppOpenWithInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_AppOpenWithInfo__ctor">AppOpenWithInfo(FileInfo)</a></td><td>
Initializes a new instance of the AppOpenWithInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_AppOpenWithInfo__ctor_1">AppOpenWithInfo(String)</a></td><td>
Initializes a new instance of the AppOpenWithInfo class.</td></tr></table>&nbsp;
<a href="#appopenwithinfo-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_DefaultIcon">DefaultIcon</a></td><td>
Gets or sets the default icon to represent the application.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_FriendlyAppName">FriendlyAppName</a></td><td>
Gets or sets the localizable name to display for an application instead of just the version information appearing, which may not be localizable. 

 The association query ASSOCSTR reads this registry entry value and falls back to use the FileDescription name in the version information. If that name is missing, the association query defaults to the display name of the file. 

 Applications should use ASSOCSTR_FRIENDLYAPPNAME to retrieve this information to obtain the proper behavior.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_IsHostApp">IsHostApp</a></td><td>
Gets or sets a value indicating whether the process is a host process, such as Rundll32.exe or Dllhost.exe, and should not be considered for Start menu pinning or inclusion in the Most Frequently Used (MFU) list. 

 When launched with a shortcut that contains a non-null argument list or an explicit Application User Model IDs (AppUserModelIDs), the process can be pinned (as that shortcut). Such shortcuts are candidates for inclusion in the MFU list.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_NoOpenWith">NoOpenWith</a></td><td>
Gets or sets a value indicating whether cc. 

 Be aware that if an OpenWithProgIDs subkey has been set for an application by file type, and the ProgID subkey itself does not also have a NoOpenWith entry, that application will appear in the list of recommended or available applications even if it has specified the NoOpenWith entry.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_NoStartPage">NoStartPage</a></td><td>
Gets or sets a value indicating whether the application executable and shortcuts should be excluded from the Start menu and from pinning or inclusion in the MFU list. 

 This entry is typically used to exclude system tools, installers and uninstallers, and readme files.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_SupportedTypes">SupportedTypes</a></td><td>
Gets or sets the file types that the application supports. 

 Doing so enables the application to be listed in the cascade menu of the Open with dialog box.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_TaskbarGroupIcon">TaskbarGroupIcon</a></td><td>
Gets or sets the icon used to override the taskbar icon. The window icon is normally used for the taskbar. 

 Setting the TaskbarGroupIcon entry causes the system to use the icon from the .exe for the application instead.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_UseExecutableForTaskbarGroupIcon">UseExecutableForTaskbarGroupIcon</a></td><td>
Gets or sets a value indicating whether to use the default icon of this executable in the taskbar if there is no pinnable shortcut for this application, and instead of the icon of the window that was first encountered.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_AppOpenWithInfo_Verb">Verb</a></td><td>
Gets or sets the verb method for calling the application from OpenWith menu. 

 Without a verb definition specified here, the system assumes that the application supports CreateProcess, and passes the file name on the command line. 

 This functionality applies to all the verb methods, including DropTarget, ExecuteCommand, and Dynamic Data Exchange (DDE).</td></tr></table>&nbsp;
<a href="#appopenwithinfo-class">Back to Top</a>

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
<a href="#appopenwithinfo-class">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ee872121%28v=vs.85%29.aspx#applications</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Program Files (x86)\MP3 Gain\MP3GainGUI.exe")
Dim info As New AppOpenWithInfo(file)

With info
    .FriendlyAppName = Path.GetFileNameWithoutExtension(file.Name)
    .Verb = String.Format("""{0}"" ""%1""", file.FullName)
    .DefaultIcon = String.Format("""{0}"",0", file.FullName)
    .TaskbarGroupIcon = info.DefaultIcon
    .SupportedTypes = {".mp2", ".mp3"}
    .IsHostApp = False
    .NoOpenWith = False
    .NoStartPage = False
    .UseExecutableForTaskbarGroupIcon = False
End With
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />