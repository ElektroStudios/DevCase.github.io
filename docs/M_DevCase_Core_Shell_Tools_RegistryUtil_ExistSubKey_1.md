# RegistryUtil.ExistSubKey Method (RegistryView, String, String)
 

Determines whether a registry subkey exists.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExistSubKey(
	RegistryView view,
	string rootKeyName,
	string subKeyPath
)
```

**VB**<br />
``` VB
Public Shared Function ExistSubKey ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ExistSubKey(view, 
	rootKeyName, subKeyPath)
```

**C++**<br />
``` C++
public:
static bool ExistSubKey(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath
)
```

**F#**<br />
``` F#
static member ExistSubKey : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExistSubKey(Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if subkey exist, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExistSubKey">ExistSubKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />