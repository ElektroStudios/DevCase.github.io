# AppConfig Class
 

Contains AppConfig related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Settings.Tools.AppConfig<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class AppConfig : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class AppConfig
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppConfig
```

**C++**<br />
``` C++
public ref class AppConfig sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type AppConfig =  
    class
        inherit AestheticObject
    end
```

The AppConfig type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_Tools_AppConfig_DirectoryPath">DirectoryPath</a></td><td>
Gets the app-config directory path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_Tools_AppConfig_FilePath">FilePath</a></td><td>
Gets the app-config filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_Application_Settings_Tools_AppConfig_PerformanceCountersEnabled">PerformanceCountersEnabled</a></td><td>
Determines whether the performance counters feature is enabled in the application configuration file (app.config) of the current application.</td></tr></table>&nbsp;
<a href="#appconfig-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Settings_Tools_AppConfig_GetAppConfigSetting__1">GetAppConfigSetting(T)(String, String, String, String)</a></td><td>
Gets the value of a setting declared in the application configuration file (app.config) of the specified application.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Application_Settings_Tools_AppConfig_GetAppConfigSetting__1_1">GetAppConfigSetting(T)(String, String, String, String, String)</a></td><td>
Gets the value of a setting declared in the application configuration file (app.config) of the specified application.</td></tr></table>&nbsp;
<a href="#appconfig-class">Back to Top</a>

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
<a href="#appconfig-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools Namespace</a><br />