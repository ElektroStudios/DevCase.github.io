# RegistryUtil.MoveKeyTree Method (RegistryView, String, String, RegistryView, String, String)
 

Moves a registry key tree to another registry path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MoveKeyTree(
	RegistryView srcView,
	string srcRootKeyName,
	string srcSubKeyPath,
	RegistryView dstView,
	string dstRootKeyName,
	string dstSubKeyPath
)
```

**VB**<br />
``` VB
Public Shared Sub MoveKeyTree ( 
	srcView As RegistryView,
	srcRootKeyName As String,
	srcSubKeyPath As String,
	dstView As RegistryView,
	dstRootKeyName As String,
	dstSubKeyPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcView As RegistryView
Dim srcRootKeyName As String
Dim srcSubKeyPath As String
Dim dstView As RegistryView
Dim dstRootKeyName As String
Dim dstSubKeyPath As StringRegistryUtil.MoveKeyTree(srcView, srcRootKeyName, 
	srcSubKeyPath, dstView, dstRootKeyName, 
	dstSubKeyPath)
```

**C++**<br />
``` C++
public:
static void MoveKeyTree(
	RegistryView srcView, 
	String^ srcRootKeyName, 
	String^ srcSubKeyPath, 
	RegistryView dstView, 
	String^ dstRootKeyName, 
	String^ dstSubKeyPath
)
```

**F#**<br />
``` F#
static member MoveKeyTree : 
        srcView : RegistryView * 
        srcRootKeyName : string * 
        srcSubKeyPath : string * 
        dstView : RegistryView * 
        dstRootKeyName : string * 
        dstSubKeyPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="srcView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.MoveKeyTree(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>srcRootKeyName</dt><dd>Type: System.String<br />The source registry rootkey name.</dd><dt>srcSubKeyPath</dt><dd>Type: System.String<br />The source registry subkey path.</dd><dt>dstView</dt><dd>Type: Microsoft.Win32.RegistryView<br />\[Missing <param name="dstView"/> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.MoveKeyTree(Microsoft.Win32.RegistryView,System.String,System.String,Microsoft.Win32.RegistryView,System.String,System.String)"\]</dd><dt>dstRootKeyName</dt><dd>Type: System.String<br />The target registry rootkey name.</dd><dt>dstSubKeyPath</dt><dd>Type: System.String<br />The target registry subkey path.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>srcRootKeyName or srcSubKeyPath or dstRootKeyName or dstSubKeyPath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_RegistryUtil_MoveKeyTree">MoveKeyTree Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />