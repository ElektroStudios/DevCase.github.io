# DirectoryInfoExtensions.CreateZipFile Method (DirectoryInfo, FileInfo, CompressionLevel, Encoding)
 

Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with the specified compression level and character encoding for entry name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ZipArchive CreateZipFile(
	this DirectoryInfo directory,
	FileInfo destinationFile,
	CompressionLevel compressionLevel,
	Encoding entryNameEncoding
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateZipFile ( 
	directory As DirectoryInfo,
	destinationFile As FileInfo,
	compressionLevel As CompressionLevel,
	entryNameEncoding As Encoding
) As ZipArchive
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim destinationFile As FileInfo
Dim compressionLevel As CompressionLevel
Dim entryNameEncoding As Encoding
Dim returnValue As ZipArchive

returnValue = directory.CreateZipFile(destinationFile, 
	compressionLevel, entryNameEncoding)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ZipArchive^ CreateZipFile(
	DirectoryInfo^ directory, 
	FileInfo^ destinationFile, 
	CompressionLevel compressionLevel, 
	Encoding^ entryNameEncoding
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateZipFile : 
        directory : DirectoryInfo * 
        destinationFile : FileInfo * 
        compressionLevel : CompressionLevel * 
        entryNameEncoding : Encoding -> ZipArchive 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd><dt>destinationFile</dt><dd>Type: System.IO.FileInfo<br />The path of the archive to be created.</dd><dt>compressionLevel</dt><dd>Type: System.IO.Compression.CompressionLevel<br />Indicates whether to emphasize speed or compression effectiveness when creating the archive.</dd><dt>entryNameEncoding</dt><dd>Type: System.Text.Encoding<br />The encoding to use when reading or writing entry names in this archive. 

 Specify a value for this parameter only when an encoding is required for interoperability with zip archive tools and libraries that do not support UTF-8 encoding for entry names.</dd></dl>

#### Return Value
Type: ZipArchive<br />The created ZipArchive.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile">CreateZipFile Overload</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />