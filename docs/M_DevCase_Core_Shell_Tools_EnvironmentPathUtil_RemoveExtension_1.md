# EnvironmentPathUtil.RemoveExtension Method (RegistryScope, String)
 

Removes a file extension from the `PATHEXT` registry value of the specified user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveExtension(
	RegistryScope scope,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveExtension ( 
	scope As RegistryScope,
	extension As String
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim extension As StringEnvironmentPathUtil.RemoveExtension(scope, extension)
```

**C++**<br />
``` C++
public:
static void RemoveExtension(
	RegistryScope scope, 
	String^ extension
)
```

**F#**<br />
``` F#
static member RemoveExtension : 
        scope : RegistryScope * 
        extension : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to remove.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveExtension">RemoveExtension Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />