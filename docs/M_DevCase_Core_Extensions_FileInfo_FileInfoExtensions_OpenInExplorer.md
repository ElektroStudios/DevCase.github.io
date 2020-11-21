# FileInfoExtensions.OpenInExplorer Method 
 

Opens the specified file in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void OpenInExplorer(
	this FileInfo sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub OpenInExplorer ( 
	sender As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo

sender.OpenInExplorer()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void OpenInExplorer(
	FileInfo^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member OpenInExplorer : 
        sender : FileInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />