# RegistryUtil.UnloadHive Method 
 

Unloads a previously hive file that has been loaded into `HKEY_LOCAL_MACHINE` root key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void UnloadHive(
	string subkeyName
)
```

**VB**<br />
``` VB
Public Shared Sub UnloadHive ( 
	subkeyName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim subkeyName As StringRegistryUtil.UnloadHive(subkeyName)
```

**C++**<br />
``` C++
public:
static void UnloadHive(
	String^ subkeyName
)
```

**F#**<br />
``` F#
static member UnloadHive : 
        subkeyName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>subkeyName</dt><dd>Type: System.String<br />The name of the subkey to unload.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
UnloadHive("HKEY_LOCAL_MACHINE\My External Branch")
or:
UnloadHive("My External Branch")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />