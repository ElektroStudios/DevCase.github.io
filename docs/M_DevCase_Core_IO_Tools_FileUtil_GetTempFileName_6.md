# FileUtil.GetTempFileName Method (String, String)
 

Creates a uniquely named, zero-byte temporary file on the specified folder with the specified file extension and returns the file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTempFileName(
	string dirPath,
	string extension
)
```

**VB**<br />
``` VB
Public Shared Function GetTempFileName ( 
	dirPath As String,
	extension As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim extension As String
Dim returnValue As String

returnValue = FileUtil.GetTempFileName(dirPath, 
	extension)
```

**C++**<br />
``` C++
public:
static String^ GetTempFileName(
	String^ dirPath, 
	String^ extension
)
```

**F#**<br />
``` F#
static member GetTempFileName : 
        dirPath : string * 
        extension : string -> string 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The full path of the folder where to create the temporary file.</dd><dt>extension</dt><dd>Type: System.String<br />The file extension to assign to the temporary file.</dd></dl>

#### Return Value
Type: String<br />The full path of the temporary file.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>dirPath or extension</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As String = GetTempFileName("C:\Folder\", "txt")
Console.WriteLine(tmpFile)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFileName">GetTempFileName Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />