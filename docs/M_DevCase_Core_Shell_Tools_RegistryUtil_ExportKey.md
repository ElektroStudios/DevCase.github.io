# RegistryUtil.ExportKey Method (RegistryView, String, String)
 

Exports a key to a registry file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExportKey(
	RegistryView view,
	string fullKeyPath,
	string outputFile
)
```

**VB**<br />
``` VB
Public Shared Function ExportKey ( 
	view As RegistryView,
	fullKeyPath As String,
	outputFile As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim view As RegistryView
Dim fullKeyPath As String
Dim outputFile As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ExportKey(view, 
	fullKeyPath, outputFile)
```

**C++**<br />
``` C++
public:
static bool ExportKey(
	RegistryView view, 
	String^ fullKeyPath, 
	String^ outputFile
)
```

**F#**<br />
``` F#
static member ExportKey : 
        view : RegistryView * 
        fullKeyPath : string * 
        outputFile : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>view</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="view"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.ExportKey(Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>fullKeyPath</dt><dd>Type: System.String<br />The registry key full path.</dd><dt>outputFile</dt><dd>Type: System.String<br />The output file.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_ExportKey">ExportKey Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />