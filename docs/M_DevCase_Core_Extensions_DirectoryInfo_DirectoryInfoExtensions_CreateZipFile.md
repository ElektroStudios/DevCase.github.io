# DirectoryInfoExtensions.CreateZipFile Method (DirectoryInfo)
 

Creates a zip archive that contains the files and directories from the specified directory, using the source folder name to create the zip file, with Optimal compression level and UTF8 character encoding for entry name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ZipArchive CreateZipFile(
	this DirectoryInfo directory
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateZipFile ( 
	directory As DirectoryInfo
) As ZipArchive
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim returnValue As ZipArchive

returnValue = directory.CreateZipFile()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ZipArchive^ CreateZipFile(
	DirectoryInfo^ directory
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateZipFile : 
        directory : DirectoryInfo -> ZipArchive 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd></dl>

#### Return Value
Type: ZipArchive<br />The created ZipArchive.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile">CreateZipFile Overload</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />