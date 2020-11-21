# RegistryUtil.CreateValue(*T*) Method (RegInfo(*T*))
 

Creates or replaces a registry value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CreateValue<T>(
	RegInfo<T> regInfo
)

```

**VB**<br />
``` VB
Public Shared Sub CreateValue(Of T) ( 
	regInfo As RegInfo(Of T)
)
```

**VB Usage**<br />
``` VB Usage
Dim regInfo As RegInfo(Of T)

RegistryUtil.CreateValue(regInfo)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void CreateValue(
	RegInfo<T>^ regInfo
)
```

**F#**<br />
``` F#
static member CreateValue : 
        regInfo : RegInfo<'T> -> unit 

```


#### Parameters
&nbsp;<dl><dt>regInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegInfo_1">DevCase.Core.Shell.RegInfo</a>(*T*)<br />A <a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T)</a> instance containing the registry info.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CreateValue">CreateValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />