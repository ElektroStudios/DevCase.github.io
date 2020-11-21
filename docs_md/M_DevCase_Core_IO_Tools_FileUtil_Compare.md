# FileUtil.Compare Method (FileInfo, FileInfo)
 

Compares two files byte by byte to determine if they are equals.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Compare(
	FileInfo fileA,
	FileInfo fileB
)
```

**VB**<br />
``` VB
Public Shared Function Compare ( 
	fileA As FileInfo,
	fileB As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim fileA As FileInfo
Dim fileB As FileInfo
Dim returnValue As Boolean

returnValue = FileUtil.Compare(fileA, 
	fileB)
```

**C++**<br />
``` C++
public:
static bool Compare(
	FileInfo^ fileA, 
	FileInfo^ fileB
)
```

**F#**<br />
``` F#
static member Compare : 
        fileA : FileInfo * 
        fileB : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>fileA</dt><dd>Type: System.IO.FileInfo<br />The first file.</dd><dt>fileB</dt><dd>Type: System.IO.FileInfo<br />The second file.</dd></dl>

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