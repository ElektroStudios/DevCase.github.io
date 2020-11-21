# AppUtil.GetFirstRunFlag Method 
 

Gets the first run flag registry.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool GetFirstRunFlag(
	RegistryScope scope,
	string aplicationName
)
```

**VB**<br />
``` VB
Public Shared Function GetFirstRunFlag ( 
	scope As RegistryScope,
	aplicationName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim aplicationName As String
Dim returnValue As Boolean

returnValue = AppUtil.GetFirstRunFlag(scope, 
	aplicationName)
```

**C++**<br />
``` C++
public:
static bool GetFirstRunFlag(
	RegistryScope scope, 
	String^ aplicationName
)
```

**F#**<br />
``` F#
static member GetFirstRunFlag : 
        scope : RegistryScope * 
        aplicationName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>aplicationName</dt><dd>Type: System.String<br />The name of the aplication.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if this is the first run of the current application, `false` (`False` in Visual Basic) otherwise.

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