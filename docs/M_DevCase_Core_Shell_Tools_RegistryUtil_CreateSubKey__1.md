# RegistryUtil.CreateSubKey(*T*) Method (RegInfo(*T*), RegistryKeyPermissionCheck, RegistryOptions)
 

Creates a new registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RegInfo<T> CreateSubKey<T>(
	RegInfo<T> regInfo,
	RegistryKeyPermissionCheck registryKeyPermissionCheck = 0,
	RegistryOptions registryOptions = 0
)

```

**VB**<br />
``` VB
Public Shared Function CreateSubKey(Of T) ( 
	regInfo As RegInfo(Of T),
	Optional registryKeyPermissionCheck As RegistryKeyPermissionCheck = 0,
	Optional registryOptions As RegistryOptions = 0
) As RegInfo(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim regInfo As RegInfo(Of T)
Dim registryKeyPermissionCheck As RegistryKeyPermissionCheck
Dim registryOptions As RegistryOptions
Dim returnValue As RegInfo(Of T)

returnValue = RegistryUtil.CreateSubKey(regInfo, 
	registryKeyPermissionCheck, registryOptions)
```

**C++**<br />
``` C++
public:
generic<typename T>
static RegInfo<T>^ CreateSubKey(
	RegInfo<T>^ regInfo, 
	RegistryKeyPermissionCheck registryKeyPermissionCheck = 0, 
	RegistryOptions registryOptions = 0
)
```

**F#**<br />
``` F#
static member CreateSubKey : 
        regInfo : RegInfo<'T> * 
        ?registryKeyPermissionCheck : RegistryKeyPermissionCheck * 
        ?registryOptions : RegistryOptions 
(* Defaults:
        let _registryKeyPermissionCheck = defaultArg registryKeyPermissionCheck 0
        let _registryOptions = defaultArg registryOptions 0
*)
-> RegInfo<'T> 

```


#### Parameters
&nbsp;<dl><dt>regInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegInfo_1">DevCase.Core.Shell.RegInfo</a>(*T*)<br />A <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T)</a> instance containing the registry info.</dd><dt>registryKeyPermissionCheck (Optional)</dt><dd>Type: Microsoft.Win32.RegistryKeyPermissionCheck<br />The registry key permission check.</dd><dt>registryOptions (Optional)</dt><dd>Type: Microsoft.Win32.RegistryOptions<br />The registry options.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo</a>(*T*)<br />The registry key.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CreateSubKey">CreateSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />