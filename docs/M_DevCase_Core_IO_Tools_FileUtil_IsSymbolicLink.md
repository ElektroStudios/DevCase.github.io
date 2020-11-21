# FileUtil.IsSymbolicLink Method (FileInfo)
 

Determines whether whether the specified file is a symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsSymbolicLink(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function IsSymbolicLink ( 
	file As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As Boolean

returnValue = FileUtil.IsSymbolicLink(file)
```

**C++**<br />
``` C++
public:
static bool IsSymbolicLink(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member IsSymbolicLink : 
        file : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The file.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified file is a symbolic link; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_IsSymbolicLink">IsSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />