# DirectoryUtil.IsSymbolicLink Method (DirectoryInfo)
 

Determines whether whether the specified directory is a symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsSymbolicLink(
	DirectoryInfo directory
)
```

**VB**<br />
``` VB
Public Shared Function IsSymbolicLink ( 
	directory As DirectoryInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim returnValue As Boolean

returnValue = DirectoryUtil.IsSymbolicLink(directory)
```

**C++**<br />
``` C++
public:
static bool IsSymbolicLink(
	DirectoryInfo^ directory
)
```

**F#**<br />
``` F#
static member IsSymbolicLink : 
        directory : DirectoryInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The directory.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified directory is a symbolic link; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_IsSymbolicLink">IsSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />