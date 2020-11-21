# FileUtil.GetSize Method 
 

Gets the size of a file, in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long GetSize(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetSize ( 
	filepath As String
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Long

returnValue = FileUtil.GetSize(filepath)
```

**C++**<br />
``` C++
public:
static long long GetSize(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetSize : 
        filepath : string -> int64 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd></dl>

#### Return Value
Type: Int64<br />The file size, in bytes.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filesize As Long = GetSize("C:\File.ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />