# RegistryUtil.CopyValue Method (RegistryView, String, String, RegistryView, String, String)
 

Copies a registry value (with its data) to another subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CopyValue(
	RegistryView srcView,
	string srcFullKeyPath,
	string srcValueName,
	RegistryView dstView,
	string dstFullKeyPath,
	string dstValueName
)
```

**VB**<br />
``` VB
Public Shared Sub CopyValue ( 
	srcView As RegistryView,
	srcFullKeyPath As String,
	srcValueName As String,
	dstView As RegistryView,
	dstFullKeyPath As String,
	dstValueName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcView As RegistryView
Dim srcFullKeyPath As String
Dim srcValueName As String
Dim dstView As RegistryView
Dim dstFullKeyPath As String
Dim dstValueName As StringRegistryUtil.CopyValue(srcView, srcFullKeyPath, 
	srcValueName, dstView, dstFullKeyPath, 
	dstValueName)
```

**C++**<br />
``` C++
public:
static void CopyValue(
	RegistryView srcView, 
	String^ srcFullKeyPath, 
	String^ srcValueName, 
	RegistryView dstView, 
	String^ dstFullKeyPath, 
	String^ dstValueName
)
```

**F#**<br />
``` F#
static member CopyValue : 
        srcView : RegistryView * 
        srcFullKeyPath : string * 
        srcValueName : string * 
        dstView : RegistryView * 
        dstFullKeyPath : string * 
        dstValueName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="srcView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopyValue(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>srcFullKeyPath</dt><dd>Type: System.String<br />The source registry key full path.</dd><dt>srcValueName</dt><dd>Type: System.String<br />The source registry value name.</dd><dt>dstView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="dstView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopyValue(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>dstFullKeyPath</dt><dd>Type: System.String<br />The target registry key full path.</dd><dt>dstValueName</dt><dd>Type: System.String<br />The target registry value name.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CopyValue">CopyValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />