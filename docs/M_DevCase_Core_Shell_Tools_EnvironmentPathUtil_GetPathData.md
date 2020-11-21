# EnvironmentPathUtil.GetPathData Method 
 

Gets the data of the `PATH` registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string[] GetPathData(
	RegistryScope scope
)
```

**VB**<br />
``` VB
Public Shared Function GetPathData ( 
	scope As RegistryScope
) As String()
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim returnValue As String()

returnValue = EnvironmentPathUtil.GetPathData(scope)
```

**C++**<br />
``` C++
public:
static array<String^>^ GetPathData(
	RegistryScope scope
)
```

**F#**<br />
``` F#
static member GetPathData : 
        scope : RegistryScope -> string[] 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd></dl>

#### Return Value
Type: String[]<br />The data of the `PATH` registry value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />