# RegistryUtil.ValueIsEmpty Method (RegistryView, String, String, String)
 

Determines whether a registry value is empty.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ValueIsEmpty(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	string valueName
)
```

**VB**<br />
``` VB
Public Shared Function ValueIsEmpty ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	valueName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim valueName As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ValueIsEmpty(view, 
	rootKeyName, subKeyPath, valueName)
```

**C++**<br />
``` C++
public:
static bool ValueIsEmpty(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	String^ valueName
)
```

**F#**<br />
``` F#
static member ValueIsEmpty : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        valueName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ValueIsEmpty(Microsoft.Win32.RegistryView,System.String,System.String,System.String)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>valueName</dt><dd>Type: System.String<br />The value name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if value is empty, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath or valueName</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ValueIsEmpty">ValueIsEmpty Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />