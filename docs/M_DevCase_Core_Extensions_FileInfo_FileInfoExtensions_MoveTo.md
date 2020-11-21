# FileInfoExtensions.MoveTo Method (FileInfo, DirectoryInfo)
 

Moves the source file to the specified directory. 

 If the target file already exists, an IOException is thrown.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveTo(
	this FileInfo sender,
	DirectoryInfo targetDirectory
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveTo ( 
	sender As FileInfo,
	targetDirectory As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim targetDirectory As DirectoryInfo

sender.MoveTo(targetDirectory)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveTo(
	FileInfo^ sender, 
	DirectoryInfo^ targetDirectory
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveTo : 
        sender : FileInfo * 
        targetDirectory : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd><dt>targetDirectory</dt><dd>Type: System.IO.DirectoryInfo<br />The target directory.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_MoveTo">MoveTo Overload</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />