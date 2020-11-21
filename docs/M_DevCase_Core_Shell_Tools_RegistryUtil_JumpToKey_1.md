# RegistryUtil.JumpToKey Method (RegistryView, String, String)
 

Runs Regedit.exe process to jump at the specified key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void JumpToKey(
	RegistryView view,
	string rootKeyName,
	string subKeyPath
)
```

**VB**<br />
``` VB
Public Shared Sub JumpToKey ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As StringRegistryUtil.JumpToKey(view, rootKeyName, 
	subKeyPath)
```

**C++**<br />
``` C++
public:
static void JumpToKey(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath
)
```

**F#**<br />
``` F#
static member JumpToKey : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.JumpToKey(Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_JumpToKey">JumpToKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />