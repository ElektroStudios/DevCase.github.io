# AppUtil.SetFirstRunFlag Method 
 

Writes a registry value with name `IsFirstRun` under the `HKCU\SOFTWARE\{Application Name}\` registry key to evaluate whether this is the first run of the current application in any next application runs. 

 The flag is

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetFirstRunFlag(
	RegistryScope scope,
	string aplicationName,
	bool value
)
```

**VB**<br />
``` VB
Public Shared Sub SetFirstRunFlag ( 
	scope As RegistryScope,
	aplicationName As String,
	value As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim aplicationName As String
Dim value As BooleanAppUtil.SetFirstRunFlag(scope, aplicationName, 
	value)
```

**C++**<br />
``` C++
public:
static void SetFirstRunFlag(
	RegistryScope scope, 
	String^ aplicationName, 
	bool value
)
```

**F#**<br />
``` F#
static member SetFirstRunFlag : 
        scope : RegistryScope * 
        aplicationName : string * 
        value : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>aplicationName</dt><dd>Type: System.String<br />The name of the aplication. 

 ( or other identifier to assign the name of the registry value. )</dd><dt>value</dt><dd>Type: System.Boolean<br />Set this value to `false` (`False` in Visual Basic) if this is the first app-run. 

 Set this value to `true` (`True` in Visual Basic) for testing purposes to reset the flag, so the next application run will be threathed as the first application run.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim valueName As String = My.Application.Info.ProductName
Dim isFirstRun As Boolean = GetFirstRunFlag(RegistryScope.CurrentUser, valueName)

If (isFirstRun) Then
    SetFirstRunFlag(RegistryScope.CurrentUser, valueName, value:=False)
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />