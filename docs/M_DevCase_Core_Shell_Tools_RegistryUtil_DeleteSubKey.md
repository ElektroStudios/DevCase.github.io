# RegistryUtil.DeleteSubKey Method (RegistryView, String, Boolean)
 

Deletes a registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DeleteSubKey(
	RegistryView view,
	string fullKeyPath,
	bool throwOnMissingSubKey = false
)
```

**VB**<br />
``` VB
Public Shared Sub DeleteSubKey ( 
	view As RegistryView,
	fullKeyPath As String,
	Optional throwOnMissingSubKey As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim throwOnMissingSubKey As BooleanRegistryUtil.DeleteSubKey(view, fullKeyPath, 
	throwOnMissingSubKey)
```

**C++**<br />
``` C++
public:
static void DeleteSubKey(
	RegistryView view, 
	String^ fullKeyPath, 
	bool throwOnMissingSubKey = false
)
```

**F#**<br />
``` F#
static member DeleteSubKey : 
        view : RegistryView * 
        fullKeyPath : string * 
        ?throwOnMissingSubKey : bool 
(* Defaults:
        let _throwOnMissingSubKey = defaultArg throwOnMissingSubKey false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.DeleteSubKey(Microsoft.Win32.RegistryView,System.String,System.Boolean)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>throwOnMissingSubKey (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an exception on missing subkey.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey">DeleteSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />