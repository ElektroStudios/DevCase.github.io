# RegistryUtil.ExistValue Method (RegistryView, String, String)
 

Determines whether a registry subkey exists.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExistValue(
	RegistryView view,
	string fullKeyPath,
	string valueName
)
```

**VB**<br />
``` VB
Public Shared Function ExistValue ( 
	view As RegistryView,
	fullKeyPath As String,
	valueName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim valueName As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ExistValue(view, 
	fullKeyPath, valueName)
```

**C++**<br />
``` C++
public:
static bool ExistValue(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ valueName
)
```

**F#**<br />
``` F#
static member ExistValue : 
        view : RegistryView * 
        fullKeyPath : string * 
        valueName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExistValue(Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if subkey exist, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExistValue">ExistValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />