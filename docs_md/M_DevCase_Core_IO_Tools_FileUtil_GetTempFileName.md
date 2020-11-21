# FileUtil.GetTempFileName Method 
 

Creates a uniquely named, zero-byte temporary file on the system's default temporary folder and returns the file path.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetTempFileName()
```

**VB**<br />
``` VB
Public Shared Function GetTempFileName As String
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As String

returnValue = FileUtil.GetTempFileName()
```

**C++**<br />
``` C++
public:
static String^ GetTempFileName()
```

**F#**<br />
``` F#
static member GetTempFileName : unit -> string 

```


#### Return Value
Type: String<br />The full path of the temporary file.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim tmpFile As String = GetTempFileName()
Console.WriteLine(tmpFile)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetTempFileName">GetTempFileName Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />