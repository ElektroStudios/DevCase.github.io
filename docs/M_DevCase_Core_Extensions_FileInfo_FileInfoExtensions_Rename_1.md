# FileInfoExtensions.Rename Method (FileInfo, String, String)
 

Renames the name of the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Rename(
	this FileInfo sender,
	string name,
	string extension
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Rename ( 
	sender As FileInfo,
	name As String,
	extension As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As FileInfo
Dim name As String
Dim extension As String

sender.Rename(name, extension)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Rename(
	FileInfo^ sender, 
	String^ name, 
	String^ extension
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Rename : 
        sender : FileInfo * 
        name : string * 
        extension : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd><dt>name</dt><dd>Type: System.String<br />The new name of the file.</dd><dt>extension</dt><dd>Type: System.String<br />The new extension (with or without a leading period). 

 You can set *extension* to a null reference (`Nothing` in Visual Basic) to remove an existing extension.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Rename">Rename Overload</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />