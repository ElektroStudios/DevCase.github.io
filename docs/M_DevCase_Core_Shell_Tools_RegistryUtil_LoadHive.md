# RegistryUtil.LoadHive Method 
 

Loads the subkeys of a hive file, creating a subkey with the specified name into `HKEY_LOCAL_MACHINE` root key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void LoadHive(
	string filepath,
	string subkeyName
)
```

**VB**<br />
``` VB
Public Shared Sub LoadHive ( 
	filepath As String,
	subkeyName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim subkeyName As StringRegistryUtil.LoadHive(filepath, subkeyName)
```

**C++**<br />
``` C++
public:
static void LoadHive(
	String^ filepath, 
	String^ subkeyName
)
```

**F#**<br />
``` F#
static member LoadHive : 
        filepath : string * 
        subkeyName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The hive filepath.</dd><dt>subkeyName</dt><dd>Type: System.String<br />The name to give to the loaded subkey.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
LoadHive("C:\WinMount\Users\Administrador\NTUSER.DAT", "My External Branch")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />