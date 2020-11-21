# EnvironmentPathUtil.AddExtension Method 
 

Adds a file extension into the `PATHEXT` registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddExtension(
	RegistryScope scope,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Sub AddExtension ( 
	scope As RegistryScope,
	extension As String
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim extension As StringEnvironmentPathUtil.AddExtension(scope, extension)
```

**C++**<br />
``` C++
public:
static void AddExtension(
	RegistryScope scope, 
	String^ extension
)
```

**F#**<br />
``` F#
static member AddExtension : 
        scope : RegistryScope * 
        extension : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to add.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />