# RegistryUtil.DeleteValue Method (RegistryView, String, String, Boolean)
 

Deletes a registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DeleteValue(
	RegistryView view,
	string fullKeyPath,
	string valueName,
	bool throwOnMissingValue = false
)
```

**VB**<br />
``` VB
Public Shared Sub DeleteValue ( 
	view As RegistryView,
	fullKeyPath As String,
	valueName As String,
	Optional throwOnMissingValue As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim valueName As String
Dim throwOnMissingValue As BooleanRegistryUtil.DeleteValue(view, fullKeyPath, 
	valueName, throwOnMissingValue)
```

**C++**<br />
``` C++
public:
static void DeleteValue(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ valueName, 
	bool throwOnMissingValue = false
)
```

**F#**<br />
``` F#
static member DeleteValue : 
        view : RegistryView * 
        fullKeyPath : string * 
        valueName : string * 
        ?throwOnMissingValue : bool 
(* Defaults:
        let _throwOnMissingValue = defaultArg throwOnMissingValue false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.DeleteValue(Microsoft.Win32.RegistryView,System.String,System.String,System.Boolean)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd><dt>throwOnMissingValue (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an exception on missing value.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_DeleteValue">DeleteValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />