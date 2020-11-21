# FileUtil.GetTempFile Method 
 

Creates a uniquely named, zero-byte temporary file on the system's default temporary folder and returns the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileInfo GetTempFile()
```

**VB**<br />
``` VB
Public Shared Function GetTempFile As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As FileInfo

returnValue = FileUtil.GetTempFile()
```

**C++**<br />
``` C++
public:
static FileInfo^ GetTempFile()
```

**F#**<br />
``` F#
static member GetTempFile : unit -> FileInfo 

```


#### Return Value
Type: FileInfo<br />The resulting FileInfo.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As FileInfo = GetTempFile()
Console.WriteLine(tmpFile.FullName)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFile">GetTempFile Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />