# FileUtil.GetAttributes Method 
 

Gets the attributes of a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileAttributes GetAttributes(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetAttributes ( 
	filepath As String
) As FileAttributes
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As FileAttributes

returnValue = FileUtil.GetAttributes(filepath)
```

**C++**<br />
``` C++
public:
static FileAttributes GetAttributes(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetAttributes : 
        filepath : string -> FileAttributes 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd></dl>

#### Return Value
Type: FileAttributes<br />The file attributes.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim attributes As FileAttributes = GetAttributes("C:\File.ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />