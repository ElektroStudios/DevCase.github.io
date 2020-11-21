# RegistryUtil.JumpToKey Method (RegistryView, String)
 

Runs Registry.exe process to jump at the specified key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void JumpToKey(
	RegistryView view,
	string fullKeyPath
)
```

**VB**<br />
``` VB
Public Shared Sub JumpToKey ( 
	view As RegistryView,
	fullKeyPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As StringRegistryUtil.JumpToKey(view, fullKeyPath)
```

**C++**<br />
``` C++
public:
static void JumpToKey(
	RegistryView view, 
	String^ fullKeyPath
)
```

**F#**<br />
``` F#
static member JumpToKey : 
        view : RegistryView * 
        fullKeyPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.JumpToKey(Microsoft.Win32.RegistryView,System.String)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_JumpToKey">JumpToKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />