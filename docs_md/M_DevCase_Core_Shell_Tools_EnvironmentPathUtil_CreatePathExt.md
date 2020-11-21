# EnvironmentPathUtil.CreatePathExt Method 
 

Creates an empty `PATHEXT` value in the registry. 

 Optionally fills the value with the specified data.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreatePathExt(
	RegistryScope scope,
	string data = ""
)
```

**VB**<br />
``` VB
Public Shared Sub CreatePathExt ( 
	scope As RegistryScope,
	Optional data As String = ""
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim data As StringEnvironmentPathUtil.CreatePathExt(scope, data)
```

**C++**<br />
``` C++
public:
static void CreatePathExt(
	RegistryScope scope, 
	String^ data = L""
)
```

**F#**<br />
``` F#
static member CreatePathExt : 
        scope : RegistryScope * 
        ?data : string 
(* Defaults:
        let _data = defaultArg data ""
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>data (Optional)</dt><dd>Type: System.String<br />The `PATHEXT` data.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />