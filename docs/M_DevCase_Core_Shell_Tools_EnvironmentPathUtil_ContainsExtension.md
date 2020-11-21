# EnvironmentPathUtil.ContainsExtension Method 
 

Determines whether the `PATHEXT` registry value contains the specified file extension.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ContainsExtension(
	RegistryScope scope,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Function ContainsExtension ( 
	scope As RegistryScope,
	extension As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim extension As String
Dim returnValue As Boolean

returnValue = EnvironmentPathUtil.ContainsExtension(scope, 
	extension)
```

**C++**<br />
``` C++
public:
static bool ContainsExtension(
	RegistryScope scope, 
	String^ extension
)
```

**F#**<br />
``` F#
static member ContainsExtension : 
        scope : RegistryScope * 
        extension : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to examine.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if it contains the specified file extension; `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />