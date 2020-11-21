# RegistryUtil.GetRootKeyName Method 
 

Gets the root key name of a registry path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetRootKeyName(
	string registryPath
)
```

**VB**<br />
``` VB
Public Shared Function GetRootKeyName ( 
	registryPath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim registryPath As String
Dim returnValue As String

returnValue = RegistryUtil.GetRootKeyName(registryPath)
```

**C++**<br />
``` C++
public:
static String^ GetRootKeyName(
	String^ registryPath
)
```

**F#**<br />
``` F#
static member GetRootKeyName : 
        registryPath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>registryPath</dt><dd>Type: System.String<br />\[Missing <param name="registryPath"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.GetRootKeyName(System.String)"\]</dd></dl>

#### Return Value
Type: String<br />The root key name of a registry path.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />