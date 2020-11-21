# FileUtil.Compare Method (String, String)
 

Compares two files byte by byte to determine if they are equals.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Compare(
	string fileA,
	string fileB
)
```

**VB**<br />
``` VB
Public Shared Function Compare ( 
	fileA As String,
	fileB As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim fileA As String
Dim fileB As String
Dim returnValue As Boolean

returnValue = FileUtil.Compare(fileA, 
	fileB)
```

**C++**<br />
``` C++
public:
static bool Compare(
	String^ fileA, 
	String^ fileB
)
```

**F#**<br />
``` F#
static member Compare : 
        fileA : string * 
        fileB : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>fileA</dt><dd>Type: System.String<br />The first file.</dd><dt>fileB</dt><dd>Type: System.String<br />The second file.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if files are equals, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim equals As Boolean = Compare("C:\File1.ext", "C:\file2.ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_Compare">Compare Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />