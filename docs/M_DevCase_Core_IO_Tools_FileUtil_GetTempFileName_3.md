# FileUtil.GetTempFileName Method (DirectoryInfo)
 

Creates a uniquely named, zero-byte temporary file on the specified folder and returns the file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTempFileName(
	DirectoryInfo dir
)
```

**VB**<br />
``` VB
Public Shared Function GetTempFileName ( 
	dir As DirectoryInfo
) As String
```

**VB Usage**<br />
``` VB Usage
Dim dir As DirectoryInfo
Dim returnValue As String

returnValue = FileUtil.GetTempFileName(dir)
```

**C++**<br />
``` C++
public:
static String^ GetTempFileName(
	DirectoryInfo^ dir
)
```

**F#**<br />
``` F#
static member GetTempFileName : 
        dir : DirectoryInfo -> string 

```


#### Parameters
&nbsp;<dl><dt>dir</dt><dd>Type: System.IO.DirectoryInfo<br />The folder where to create the temporary file.</dd></dl>

#### Return Value
Type: String<br />The full path of the temporary file.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As String = GetTempFileName(New DirectoryInfo("C:\Folder\"))
Console.WriteLine(tmpFile)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFileName">GetTempFileName Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />