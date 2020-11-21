# EnvironmentPathUtil.AddDirectory Method 
 

Adds a directory into the `PATH` registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddDirectory(
	RegistryScope scope,
	string directory
)
```

**VB**<br />
``` VB
Public Shared Sub AddDirectory ( 
	scope As RegistryScope,
	directory As String
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim directory As StringEnvironmentPathUtil.AddDirectory(scope, directory)
```

**C++**<br />
``` C++
public:
static void AddDirectory(
	RegistryScope scope, 
	String^ directory
)
```

**F#**<br />
``` F#
static member AddDirectory : 
        scope : RegistryScope * 
        directory : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>directory</dt><dd>Type: System.String<br />The directory path to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Directory contains invalid characters.;directory</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />