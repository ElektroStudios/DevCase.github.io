# RegistryUtil.CopyValue Method (RegistryView, String, String, String, RegistryView, String, String, String)
 

Copies a registry value (with its data) to another subkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CopyValue(
	RegistryView srcView,
	string srcRootKeyName,
	string srcSubKeyPath,
	string srcValueName,
	RegistryView dstView,
	string dstRootKeyName,
	string dstSubKeyPath,
	string dstValueName
)
```

**VB**<br />
``` VB
Public Shared Sub CopyValue ( 
	srcView As RegistryView,
	srcRootKeyName As String,
	srcSubKeyPath As String,
	srcValueName As String,
	dstView As RegistryView,
	dstRootKeyName As String,
	dstSubKeyPath As String,
	dstValueName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcView As RegistryView
Dim srcRootKeyName As String
Dim srcSubKeyPath As String
Dim srcValueName As String
Dim dstView As RegistryView
Dim dstRootKeyName As String
Dim dstSubKeyPath As String
Dim dstValueName As StringRegistryUtil.CopyValue(srcView, srcRootKeyName, 
	srcSubKeyPath, srcValueName, dstView, 
	dstRootKeyName, dstSubKeyPath, dstValueName)
```

**C++**<br />
``` C++
public:
static void CopyValue(
	RegistryView srcView, 
	String^ srcRootKeyName, 
	String^ srcSubKeyPath, 
	String^ srcValueName, 
	RegistryView dstView, 
	String^ dstRootKeyName, 
	String^ dstSubKeyPath, 
	String^ dstValueName
)
```

**F#**<br />
``` F#
static member CopyValue : 
        srcView : RegistryView * 
        srcRootKeyName : string * 
        srcSubKeyPath : string * 
        srcValueName : string * 
        dstView : RegistryView * 
        dstRootKeyName : string * 
        dstSubKeyPath : string * 
        dstValueName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="srcView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopyValue(Microsoft.Win32.RegistryView,System.String,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String,System.String)"\]</dd><dt>srcRootKeyName</dt><dd>Type: System.String<br />The source registry rootkey name.</dd><dt>srcSubKeyPath</dt><dd>Type: System.String<br />The source registry subkey path.</dd><dt>srcValueName</dt><dd>Type: System.String<br />The source registry value name.</dd><dt>dstView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="dstView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopyValue(Microsoft.Win32.RegistryView,System.String,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String,System.String)"\]</dd><dt>dstRootKeyName</dt><dd>Type: System.String<br />The target registry rootkey name.</dd><dt>dstSubKeyPath</dt><dd>Type: System.String<br />The target registry subkey path.</dd><dt>dstValueName</dt><dd>Type: System.String<br />The target registry value name.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CopyValue">CopyValue Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />