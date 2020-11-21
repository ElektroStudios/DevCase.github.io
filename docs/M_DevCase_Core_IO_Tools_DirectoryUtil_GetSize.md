# DirectoryUtil.GetSize Method 
 

Gets the size of a directory, in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetSize(
	string directoryPath,
	SearchOption searchOption
)
```

**VB**<br />
``` VB
Public Shared Function GetSize ( 
	directoryPath As String,
	searchOption As SearchOption
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As String
Dim searchOption As SearchOption
Dim returnValue As Double

returnValue = DirectoryUtil.GetSize(directoryPath, 
	searchOption)
```

**C++**<br />
``` C++
public:
static double GetSize(
	String^ directoryPath, 
	SearchOption searchOption
)
```

**F#**<br />
``` F#
static member GetSize : 
        directoryPath : string * 
        searchOption : SearchOption -> float 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The SearchOption.</dd></dl>

#### Return Value
Type: Double<br />The directory size, in bytes.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dirsize As Long = GetSize("C:\Directory\", SearchOption.AllDirectories)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />