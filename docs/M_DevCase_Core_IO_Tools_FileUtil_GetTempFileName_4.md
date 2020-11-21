# FileUtil.GetTempFileName Method (DirectoryInfo, String)
 

Creates a uniquely named, zero-byte temporary file on the specified folder with the specified file extension and returns the file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTempFileName(
	DirectoryInfo dir,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Function GetTempFileName ( 
	dir As DirectoryInfo,
	extension As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim dir As DirectoryInfo
Dim extension As String
Dim returnValue As String

returnValue = FileUtil.GetTempFileName(dir, 
	extension)
```

**C++**<br />
``` C++
public:
static String^ GetTempFileName(
	DirectoryInfo^ dir, 
	String^ extension
)
```

**F#**<br />
``` F#
static member GetTempFileName : 
        dir : DirectoryInfo * 
        extension : string -> string 

```


#### Parameters
&nbsp;<dl><dt>dir</dt><dd>Type: System.IO.DirectoryInfo<br />The folder where to create the temporary file.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to assign to the temporary file.</dd></dl>

#### Return Value
Type: String<br />The full path of the temporary file.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>extension</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As String = GetTempFileName(New DirectoryInfo("C:\Folder\"), "txt")
Console.WriteLine(tmpFile)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFileName">GetTempFileName Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />