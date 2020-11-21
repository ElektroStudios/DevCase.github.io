# RegistryUtil.GetValueData Method (RegInfo, RegistryValueOptions)
 

Gets the data of a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Object GetValueData(
	RegInfo regInfo,
	RegistryValueOptions registryValueOptions = 0
)
```

**VB**<br />
``` VB
Public Shared Function GetValueData ( 
	regInfo As RegInfo,
	Optional registryValueOptions As RegistryValueOptions = 0
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim regInfo As RegInfo
Dim registryValueOptions As RegistryValueOptions
Dim returnValue As Object

returnValue = RegistryUtil.GetValueData(regInfo, 
	registryValueOptions)
```

**C++**<br />
``` C++
public:
static Object^ GetValueData(
	RegInfo^ regInfo, 
	RegistryValueOptions registryValueOptions = 0
)
```

**F#**<br />
``` F#
static member GetValueData : 
        regInfo : RegInfo * 
        ?registryValueOptions : RegistryValueOptions 
(* Defaults:
        let _registryValueOptions = defaultArg registryValueOptions 0
*)
-> Object 

```


#### Parameters
&nbsp;<dl><dt>regInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegInfo">DevCase.Core.Shell.RegInfo</a><br />A <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T)</a> instance containing the registry info.</dd><dt>registryValueOptions (Optional)</dt><dd>Type: Microsoft.Win32.RegistryValueOptions<br />The registry value options.</dd></dl>

#### Return Value
Type: Object<br />The value data.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_GetValueData">GetValueData Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />