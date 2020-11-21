# FileTypeUtil.GetFileTypeMatches Method (String, FileType[])
 

Tries to detect the file type of the specified file by analyzing a collection of file type signatures on the file header, then returns a List(T) that contains the success percentage (0%...100%) of each file type found (if any).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<FileTypeMatch> GetFileTypeMatches(
	string filepath,
	FileType[] filetypes
)
```

**VB**<br />
``` VB
Public Shared Function GetFileTypeMatches ( 
	filepath As String,
	filetypes As FileType()
) As List(Of FileTypeMatch)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim filetypes As FileType()
Dim returnValue As List(Of FileTypeMatch)

returnValue = FileTypeUtil.GetFileTypeMatches(filepath, 
	filetypes)
```

**C++**<br />
``` C++
public:
static List<FileTypeMatch^>^ GetFileTypeMatches(
	String^ filepath, 
	array<FileType^>^ filetypes
)
```

**F#**<br />
``` F#
static member GetFileTypeMatches : 
        filepath : string * 
        filetypes : FileType[] -> List<FileTypeMatch> 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source file.</dd><dt>filetypes</dt><dd>Type: <a href="T_DevCase_Core_IO_FileType">DevCase.Core.IO.FileType</a>[]<br />A set of file types to match in the file header.</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch</a>)<br />A List(T) which contains the match results of the file types that were found (if any) in the file header.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filetypes As FileType() = FileTypeUtil.FiletypesDict("reg")
Dim matches As List(Of FileTypeMatch) = GetFileTypeMatches(New FileInfo("C:\Registry File.reg"), filetypes)

If (filetypeMatches.Count <> 0) Then

    For Each match As FileTypeMatch In matches
        Console.WriteLine("
                          File Type Name.......: {0}
                          File Extension.......: {1}
                          Percent Match........: {2}%
                          Signature Count......: {3}
                          Signature Match Count: {4}",
                          match.FileType.Name, match.FileType.Extension, match.PercentMatch,
                          match.FileType.Signatures.Count, match.SignatureMatchCount)
    Next match

Else
    Console.WriteLine("Any file type match found.")

End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileTypeUtil">FileTypeUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatches">GetFileTypeMatches Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />