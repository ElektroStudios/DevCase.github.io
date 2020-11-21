# EnvironmentPathUtil.PathExtData Property 
 

Gets the data of the `PATHEXT` registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> this[
	RegistryScope scope
] { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property PathExtData ( 
	scope As RegistryScope
) As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim scope As RegistryScope
Dim value As ReadOnlyCollection(Of String)

value = EnvironmentPathUtil.PathExtData(scope)

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<String^>^ PathExtData[RegistryScope scope] {
	ReadOnlyCollection<String^>^ get (RegistryScope scope);
}
```

**F#**<br />
``` F#
static member PathExtData : ReadOnlyCollection<string> with get

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegistryScope">DevCase.Core.Shell.RegistryScope</a><br /></dd></dl>

#### Property Value
Type: ReadOnlyCollection(String)<br />The data of the `PATHEXT` registry value.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentPathUtil">EnvironmentPathUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />