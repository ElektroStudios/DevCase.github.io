# RegistryUtil.DeleteSubKey(*T*) Method (RegInfo(*T*), Boolean)
 

Deletes a registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DeleteSubKey<T>(
	RegInfo<T> regInfo,
	bool throwOnMissingSubKey = false
)

```

**VB**<br />
``` VB
Public Shared Sub DeleteSubKey(Of T) ( 
	regInfo As RegInfo(Of T),
	Optional throwOnMissingSubKey As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim regInfo As RegInfo(Of T)
Dim throwOnMissingSubKey As BooleanRegistryUtil.DeleteSubKey(regInfo, throwOnMissingSubKey)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void DeleteSubKey(
	RegInfo<T>^ regInfo, 
	bool throwOnMissingSubKey = false
)
```

**F#**<br />
``` F#
static member DeleteSubKey : 
        regInfo : RegInfo<'T> * 
        ?throwOnMissingSubKey : bool 
(* Defaults:
        let _throwOnMissingSubKey = defaultArg throwOnMissingSubKey false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>regInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegInfo_1">DevCase.Core.Shell.RegInfo</a>(*T*)<br />A <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T)</a> instance containing the registry info.</dd><dt>throwOnMissingSubKey (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an exception on missing subkey.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey">DeleteSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />