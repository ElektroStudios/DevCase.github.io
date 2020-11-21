# BatchScriptUtil.ConvertRegToBat Method (String, Boolean, Boolean, Boolean, CmdCommandRedirection)
 

Converts a Registry Script to a Batch Script.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ConvertRegToBat(
	string registryFilepath,
	bool abbreviateRootKeys = true,
	bool ignoreStartingKeys = true,
	bool forceRegistryOverwritting = true,
	CmdCommandRedirection commandRedirection = CmdCommandRedirection.None
)
```

**VB**<br />
``` VB
Public Shared Function ConvertRegToBat ( 
	registryFilepath As String,
	Optional abbreviateRootKeys As Boolean = true,
	Optional ignoreStartingKeys As Boolean = true,
	Optional forceRegistryOverwritting As Boolean = true,
	Optional commandRedirection As CmdCommandRedirection = CmdCommandRedirection.None
) As String
```

**VB Usage**<br />
``` VB Usage
Dim registryFilepath As String
Dim abbreviateRootKeys As Boolean
Dim ignoreStartingKeys As Boolean
Dim forceRegistryOverwritting As Boolean
Dim commandRedirection As CmdCommandRedirection
Dim returnValue As String

returnValue = BatchScriptUtil.ConvertRegToBat(registryFilepath, 
	abbreviateRootKeys, ignoreStartingKeys, 
	forceRegistryOverwritting, commandRedirection)
```

**C++**<br />
``` C++
public:
static String^ ConvertRegToBat(
	String^ registryFilepath, 
	bool abbreviateRootKeys = true, 
	bool ignoreStartingKeys = true, 
	bool forceRegistryOverwritting = true, 
	CmdCommandRedirection commandRedirection = CmdCommandRedirection::None
)
```

**F#**<br />
``` F#
static member ConvertRegToBat : 
        registryFilepath : string * 
        ?abbreviateRootKeys : bool * 
        ?ignoreStartingKeys : bool * 
        ?forceRegistryOverwritting : bool * 
        ?commandRedirection : CmdCommandRedirection 
(* Defaults:
        let _abbreviateRootKeys = defaultArg abbreviateRootKeys true
        let _ignoreStartingKeys = defaultArg ignoreStartingKeys true
        let _forceRegistryOverwritting = defaultArg forceRegistryOverwritting true
        let _commandRedirection = defaultArg commandRedirection CmdCommandRedirection.None
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>registryFilepath</dt><dd>Type: System.String<br />The registry file to convert.</dd><dt>abbreviateRootKeys (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the root keys will be abbreviated. 

 Example: `HKEY_CLASSES_ROOT` -> `HKCR`</dd><dt>ignoreStartingKeys (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), starting keys to add into the registry will not be converted. 

 Example: `[HKEY_CLASSES_ROOT\.ext]` -> `REG ADD "HKEY_CLASSES_ROOT\.ext"`</dd><dt>forceRegistryOverwritting (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), REG commands are forced to overwrite the registry.</dd><dt>commandRedirection (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Shell_CmdCommandRedirection">DevCase.Core.Shell.CmdCommandRedirection</a><br />Indicates whether the standard/error output of the converted Batch `REG` commands should be redirected to a null reference (`Nothing` in Visual Basic) in CMD. 

 This value can be a combination of one or more Flags.</dd></dl>

#### Return Value
Type: String<br />The resulting Batch-Script content.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim batchScript As String = ConvertRegToBat("C:\RegistryFile.reg")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_BatchScriptUtil">BatchScriptUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_BatchScriptUtil_ConvertRegToBat">ConvertRegToBat Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />