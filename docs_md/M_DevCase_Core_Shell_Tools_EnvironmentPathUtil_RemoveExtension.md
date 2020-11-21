# EnvironmentPathUtil.RemoveExtension Method (RegistryScope, Int32)
 

Removes a file extension from the PATHEXT registry value of the specified user.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveExtension(
	RegistryScope scope,
	int index
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveExtension ( 
	scope As RegistryScope,
	index As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim index As Integer

EnvironmentPathUtil.RemoveExtension(scope, index)
```

**C++**<br />
``` C++
public:
static void RemoveExtension(
	RegistryScope scope, 
	int index
)
```

**F#**<br />
``` F#
static member RemoveExtension : 
        scope : RegistryScope * 
        index : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br />The registry scope.</dd><dt>index</dt><dd>Type: System.Int32<br />The zero-based index of the file extension to remove.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>IndexOutOfRangeException</td><td>File extension index is out of range.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentPathUtil_RemoveExtension">RemoveExtension Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />