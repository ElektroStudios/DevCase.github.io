# RegistryUtil.DeleteSubKey Method (RegistryView, String, String, Boolean)
 

Deletes a registry subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DeleteSubKey(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	bool throwOnMissingSubKey = false
)
```

**VB**<br />
``` VB
Public Shared Sub DeleteSubKey ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	Optional throwOnMissingSubKey As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim throwOnMissingSubKey As BooleanRegistryUtil.DeleteSubKey(view, rootKeyName, 
	subKeyPath, throwOnMissingSubKey)
```

**C++**<br />
``` C++
public:
static void DeleteSubKey(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	bool throwOnMissingSubKey = false
)
```

**F#**<br />
``` F#
static member DeleteSubKey : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        ?throwOnMissingSubKey : bool 
(* Defaults:
        let _throwOnMissingSubKey = defaultArg throwOnMissingSubKey false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.DeleteSubKey(Microsoft.Win32.RegistryView,System.String,System.String,System.Boolean)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>throwOnMissingSubKey (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), throws an exception on missing subkey.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_DeleteSubKey">DeleteSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />