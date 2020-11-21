# DirectoryInfoExtensions.Recycle Method 
 

Sends the source directory to the Recycle Bin.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Recycle(
	this FileInfo sender,
	UIOption dialog
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Recycle ( 
	sender As FileInfo,
	dialog As UIOption
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim dialog As UIOption

sender.Recycle(dialog)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Recycle(
	FileInfo^ sender, 
	UIOption dialog
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Recycle : 
        sender : FileInfo * 
        dialog : UIOption -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source DirectoryInfo.</dd><dt>dialog</dt><dd>Type: Microsoft.VisualBasic.FileIO.UIOption<br />Specifies which dialog boxes to show when recycling.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dir As New DirectoryInfo("C:\Dir\")
dir.Recycle(UIOption.OnlyErrorDialogs)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />