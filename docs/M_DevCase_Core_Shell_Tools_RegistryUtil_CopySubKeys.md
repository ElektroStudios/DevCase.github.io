# RegistryUtil.CopySubKeys Method (RegistryView, String, RegistryView, String)
 

Copies the sub-keys of the specified registry key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CopySubKeys(
	RegistryView srcView,
	string srcFullKeyPath,
	RegistryView dstView,
	string dstFullKeyPath
)
```

**VB**<br />
``` VB
Public Shared Sub CopySubKeys ( 
	srcView As RegistryView,
	srcFullKeyPath As String,
	dstView As RegistryView,
	dstFullKeyPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcView As RegistryView
Dim srcFullKeyPath As String
Dim dstView As RegistryView
Dim dstFullKeyPath As StringRegistryUtil.CopySubKeys(srcView, srcFullKeyPath, 
	dstView, dstFullKeyPath)
```

**C++**<br />
``` C++
public:
static void CopySubKeys(
	RegistryView srcView, 
	String^ srcFullKeyPath, 
	RegistryView dstView, 
	String^ dstFullKeyPath
)
```

**F#**<br />
``` F#
static member CopySubKeys : 
        srcView : RegistryView * 
        srcFullKeyPath : string * 
        dstView : RegistryView * 
        dstFullKeyPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="srcView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopySubKeys(Microsoft.Win32.RegistryView,System.String,Microsoft.Win32.RegistryView,System.String)"\]</dd><dt>srcFullKeyPath</dt><dd>Type: System.String<br />The source registry key full path.</dd><dt>dstView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="dstView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.CopySubKeys(Microsoft.Win32.RegistryView,System.String,Microsoft.Win32.RegistryView,System.String)"\]</dd><dt>dstFullKeyPath</dt><dd>Type: System.String<br />The target registry key full path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_CopySubKeys">CopySubKeys Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />