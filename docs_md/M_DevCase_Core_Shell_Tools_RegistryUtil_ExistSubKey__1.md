# RegistryUtil.ExistSubKey(*T*) Method (RegInfo(*T*))
 

Determines whether a registry subkey exists.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExistSubKey<T>(
	RegInfo<T> reginfo
)

```

**VB**<br />
``` VB
Public Shared Function ExistSubKey(Of T) ( 
	reginfo As RegInfo(Of T)
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim reginfo As RegInfo(Of T)
Dim returnValue As Boolean

returnValue = RegistryUtil.ExistSubKey(reginfo)
```

**C++**<br />
``` C++
public:
generic<typename T>
static bool ExistSubKey(
	RegInfo<T>^ reginfo
)
```

**F#**<br />
``` F#
static member ExistSubKey : 
        reginfo : RegInfo<'T> -> bool 

```


#### Parameters
&nbsp;<dl><dt>reginfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_RegInfo_1">DevCase.Core.Shell.RegInfo</a>(*T*)<br />\[Missing <param name="reginfo"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExistSubKey``1(DevCase.Core.Shell.RegInfo{``0})"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if subkey exist, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey">ExistSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />