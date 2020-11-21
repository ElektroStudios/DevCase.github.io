# FileUtil.GetTempFile Method (Environment.SpecialFolder)
 

Creates a uniquely named, zero-byte temporary file on the specified folder and returns the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileInfo GetTempFile(
	Environment.SpecialFolder folder
)
```

**VB**<br />
``` VB
Public Shared Function GetTempFile ( 
	folder As Environment.SpecialFolder
) As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim folder As Environment.SpecialFolder
Dim returnValue As FileInfo

returnValue = FileUtil.GetTempFile(folder)
```

**C++**<br />
``` C++
public:
static FileInfo^ GetTempFile(
	Environment.SpecialFolder folder
)
```

**F#**<br />
``` F#
static member GetTempFile : 
        folder : Environment.SpecialFolder -> FileInfo 

```


#### Parameters
&nbsp;<dl><dt>folder</dt><dd>Type: System.Environment.SpecialFolder<br />The folder where to create the temporary file.</dd></dl>

#### Return Value
Type: FileInfo<br />The resulting FileInfo.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As FileInfo = GetTempFile(SpecialFolder.LocalApplicationData)
Console.WriteLine(tmpFile.FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFile">GetTempFile Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />