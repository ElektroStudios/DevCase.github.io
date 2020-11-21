# FileUtil.GetTempFile Method (DirectoryInfo, String)
 

Creates a uniquely named, zero-byte temporary file on the specified folder with the specified file extension and returns the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileInfo GetTempFile(
	DirectoryInfo dir,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Function GetTempFile ( 
	dir As DirectoryInfo,
	extension As String
) As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim dir As DirectoryInfo
Dim extension As String
Dim returnValue As FileInfo

returnValue = FileUtil.GetTempFile(dir, 
	extension)
```

**C++**<br />
``` C++
public:
static FileInfo^ GetTempFile(
	DirectoryInfo^ dir, 
	String^ extension
)
```

**F#**<br />
``` F#
static member GetTempFile : 
        dir : DirectoryInfo * 
        extension : string -> FileInfo 

```


#### Parameters
&nbsp;<dl><dt>dir</dt><dd>Type: System.IO.DirectoryInfo<br />The folder where to create the temporary file.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to assign to the temporary file.</dd></dl>

#### Return Value
Type: FileInfo<br />The resulting FileInfo.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>extension</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As FileInfo = GetTempFile(New DirectoryInfo("C:\Folder\"), "txt")
Console.WriteLine(tmpFile.FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFile">GetTempFile Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />