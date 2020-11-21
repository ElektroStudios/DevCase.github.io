# AppConfig.GetAppConfigSetting(*T*) Method (String, String, String, String)
 

Gets the value of a setting declared in the application configuration file (app.config) of the specified application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T GetAppConfigSetting<T>(
	string sectionName,
	string elementName,
	string propertyName,
	string exePath = ""
)

```

**VB**<br />
``` VB
Public Shared Function GetAppConfigSetting(Of T) ( 
	sectionName As String,
	elementName As String,
	propertyName As String,
	Optional exePath As String = ""
) As T
```

**VB Usage**<br />
``` VB Usage
Dim sectionName As String
Dim elementName As String
Dim propertyName As String
Dim exePath As String
Dim returnValue As T

returnValue = AppConfig.GetAppConfigSetting(sectionName, 
	elementName, propertyName, exePath)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T GetAppConfigSetting(
	String^ sectionName, 
	String^ elementName, 
	String^ propertyName, 
	String^ exePath = L""
)
```

**F#**<br />
``` F#
static member GetAppConfigSetting : 
        sectionName : string * 
        elementName : string * 
        propertyName : string * 
        ?exePath : string 
(* Defaults:
        let _exePath = defaultArg exePath ""
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>sectionName</dt><dd>Type: System.String<br />The name of the section.</dd><dt>elementName</dt><dd>Type: System.String<br />The name of the element.</dd><dt>propertyName</dt><dd>Type: System.String<br />The name of the property.</dd><dt>exePath (Optional)</dt><dd>Type: System.String<br />The executable path of the current or an external .NET application. If any path is specified, it assumes the current application.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />If the Section, the Element, or the Property doesn't exist, the return value is a null reference (`Nothing` in Visual Basic), otherwise, the value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As Boolean = GetAppConfigSetting(Of Boolean)("sectionName", "elementName", "propertyName")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_Tools_AppConfig">AppConfig Class</a><br /><a href="Overload_DevCase_Core_Application_Settings_Tools_AppConfig_GetAppConfigSetting">GetAppConfigSetting Overload</a><br /><a href="N_DevCase_Core_Application_Settings_Tools">DevCase.Core.Application.Settings.Tools Namespace</a><br />