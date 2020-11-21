# RegistryUtil.ExportKey Method (RegistryView, String, String, String)
 

Exports a key to a registry file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExportKey(
	RegistryView view,
	string rootKeyName,
	string subKeyPath,
	string outputFile
)
```

**VB**<br />
``` VB
Public Shared Function ExportKey ( 
	view As RegistryView,
	rootKeyName As String,
	subKeyPath As String,
	outputFile As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim rootKeyName As String
Dim subKeyPath As String
Dim outputFile As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ExportKey(view, 
	rootKeyName, subKeyPath, outputFile)
```

**C++**<br />
``` C++
public:
static bool ExportKey(
	RegistryView view, 
	String^ rootKeyName, 
	String^ subKeyPath, 
	String^ outputFile
)
```

**F#**<br />
``` F#
static member ExportKey : 
        view : RegistryView * 
        rootKeyName : string * 
        subKeyPath : string * 
        outputFile : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExportKey(Microsoft.Win32.RegistryView,System.String,System.String,System.String)"\]</dd><dt>rootKeyName</dt><dd>Type: System.String<br />The rootkey name.</dd><dt>subKeyPath</dt><dd>Type: System.String<br />The subkey path.</dd><dt>outputFile</dt><dd>Type: System.String<br />The output file.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>rootKeyName or subKeyPath or outputFile</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExportKey">ExportKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />