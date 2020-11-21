# EnvironmentPathUtil.ContainsDirectory Method 
 

Determines whether the `PATH` registry value contains the specified directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ContainsDirectory(
	RegistryScope scope,
	string directory
)
```

**VB**<br />
``` VB
Public Shared Function ContainsDirectory ( 
	scope As RegistryScope,
	directory As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim directory As String
Dim returnValue As Boolean

returnValue = EnvironmentPathUtil.ContainsDirectory(scope, 
	directory)
```

**C++**<br />
``` C++
public:
static bool ContainsDirectory(
	RegistryScope scope, 
	String^ directory
)
```

**F#**<br />
``` F#
static member ContainsDirectory : 
        scope : RegistryScope * 
        directory : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>directory</dt><dd>Type: System.String<br />The directory path to examine.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if it contains the specified directory; `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />