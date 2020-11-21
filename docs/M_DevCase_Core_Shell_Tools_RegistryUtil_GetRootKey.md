# RegistryUtil.GetRootKey Method 
 

Gets the root RegistryKey of a registry path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RegistryKey GetRootKey(
	string registryPath,
	RegistryView view
)
```

**VB**<br />
``` VB
Public Shared Function GetRootKey ( 
	registryPath As String,
	view As RegistryView
) As RegistryKey
```

**VB Usage**<br />
``` VB Usage
Dim registryPath As String
Dim view As RegistryView
Dim returnValue As RegistryKey

returnValue = RegistryUtil.GetRootKey(registryPath, 
	view)
```

**C++**<br />
``` C++
public:
static RegistryKey^ GetRootKey(
	String^ registryPath, 
	RegistryView view
)
```

**F#**<br />
``` F#
static member GetRootKey : 
        registryPath : string * 
        view : RegistryView -> RegistryKey 

```


#### Parameters
&nbsp;<dl><dt>registryPath</dt><dd>Type: System.String<br />\[Missing <param name="registryPath"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.GetRootKey(System.String,Microsoft.Win32.RegistryView)"\]</dd><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.GetRootKey(System.String,Microsoft.Win32.RegistryView)"\]</dd></dl>

#### Return Value
Type: RegistryKey<br />The root RegistryKey of a registry path.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />