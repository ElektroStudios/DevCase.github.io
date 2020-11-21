# RegistryUtil.ExistSubKey Method (RegistryView, String)
 

Determines whether a registry subkey exists.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExistSubKey(
	RegistryView view,
	string fullKeyPath
)
```

**VB**<br />
``` VB
Public Shared Function ExistSubKey ( 
	view As RegistryView,
	fullKeyPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ExistSubKey(view, 
	fullKeyPath)
```

**C++**<br />
``` C++
public:
static bool ExistSubKey(
	RegistryView view, 
	String^ fullKeyPath
)
```

**F#**<br />
``` F#
static member ExistSubKey : 
        view : RegistryView * 
        fullKeyPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExistSubKey(Microsoft.Win32.RegistryView,System.String)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if subkey exist, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey">ExistSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />