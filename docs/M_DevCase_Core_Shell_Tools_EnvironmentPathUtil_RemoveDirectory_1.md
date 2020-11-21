# EnvironmentPathUtil.RemoveDirectory Method (RegistryScope, String)
 

Removes a directory from the `PATH` registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveDirectory(
	RegistryScope scope,
	string directory
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveDirectory ( 
	scope As RegistryScope,
	directory As String
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim directory As StringEnvironmentPathUtil.RemoveDirectory(scope, directory)
```

**C++**<br />
``` C++
public:
static void RemoveDirectory(
	RegistryScope scope, 
	String^ directory
)
```

**F#**<br />
``` F#
static member RemoveDirectory : 
        scope : RegistryScope * 
        directory : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>directory</dt><dd>Type: System.String<br />The directory path to remove.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveDirectory">RemoveDirectory Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />