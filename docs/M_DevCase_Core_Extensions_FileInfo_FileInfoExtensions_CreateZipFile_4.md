# FileInfoExtensions.CreateZipFile Method (FileInfo, String)
 

Creates a zip archive from the specified file, using the specified filepath to create the zip file, with Optimal compression level.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ZipArchive CreateZipFile(
	this FileInfo file,
	string destinationFileName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateZipFile ( 
	file As FileInfo,
	destinationFileName As String
) As ZipArchive
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim destinationFileName As String
Dim returnValue As ZipArchive

returnValue = file.CreateZipFile(destinationFileName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ZipArchive^ CreateZipFile(
	FileInfo^ file, 
	String^ destinationFileName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateZipFile : 
        file : FileInfo * 
        destinationFileName : string -> ZipArchive 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd><dt>destinationFileName</dt><dd>Type: System.String<br />The path of the archive to be created, specified as a relative or absolute path. 

 A relative path is interpreted as relative to the current working directory.</dd></dl>

#### Return Value
Type: ZipArchive<br />The created ZipArchive.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile">CreateZipFile Overload</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />