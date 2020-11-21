# DirectoryUtil.GetSymbolicLinkTarget Method (DirectoryInfo)
 

Gets the target of the specified symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DirectoryInfo GetSymbolicLinkTarget(
	DirectoryInfo directory
)
```

**VB**<br />
``` VB
Public Shared Function GetSymbolicLinkTarget ( 
	directory As DirectoryInfo
) As DirectoryInfo
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim returnValue As DirectoryInfo

returnValue = DirectoryUtil.GetSymbolicLinkTarget(directory)
```

**C++**<br />
``` C++
public:
static DirectoryInfo^ GetSymbolicLinkTarget(
	DirectoryInfo^ directory
)
```

**F#**<br />
``` F#
static member GetSymbolicLinkTarget : 
        directory : DirectoryInfo -> DirectoryInfo 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The (symbolic link) directory.</dd></dl>

#### Return Value
Type: DirectoryInfo<br />The target of the specified symbolic link.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_GetSymbolicLinkTarget">GetSymbolicLinkTarget Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />