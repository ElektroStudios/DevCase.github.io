# FileTypeUtil.GetFileTypeMatch Method (String, FileType)
 

Determines whether a file type signature is match in the file header of the specified file, then returns a success percentage from `0%` to `100%` where `100%` means all the file signatures were found in the file header.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileTypeMatch GetFileTypeMatch(
	string filepath,
	FileType filetype
)
```

**VB**<br />
``` VB
Public Shared Function GetFileTypeMatch ( 
	filepath As String,
	filetype As FileType
) As FileTypeMatch
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim filetype As FileType
Dim returnValue As FileTypeMatch

returnValue = FileTypeUtil.GetFileTypeMatch(filepath, 
	filetype)
```

**C++**<br />
``` C++
public:
static FileTypeMatch^ GetFileTypeMatch(
	String^ filepath, 
	FileType^ filetype
)
```

**F#**<br />
``` F#
static member GetFileTypeMatch : 
        filepath : string * 
        filetype : FileType -> FileTypeMatch 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source file.</dd><dt>filetype</dt><dd>Type: <a href="T_DevCase_Core_IO_FileType">DevCase.Core.IO.FileType</a><br />A <a href="T_DevCase_Core_IO_FileType">FileType</a> to match in the file header.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch</a><br />Returns a <a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch</a> that contains the match result with the success percentage from `0%` to `100%` where `100%` means all the file signatures were found in the file header.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim signature As New FileSignature({26, 69, 223, 163}, offset:=0, description:="Matroska - Magic Number")
Dim filetype As New FileType(signature, "Matroska stream (generic)", "mkv", "video/x-matroska")
Dim filepath As String = "C:\File.mkv"

Dim match As FileTypeMatch = GetFileTypeMatch(filepath, filetype)
Console.WriteLine("File ""{0}"" Is File Type Of ""{1}""?: {2}%", file.Name, filetype.Name, match.PercentMatch)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileTypeUtil">FileTypeUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatch">GetFileTypeMatch Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />