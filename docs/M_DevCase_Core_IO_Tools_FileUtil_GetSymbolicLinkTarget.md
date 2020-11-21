# FileUtil.GetSymbolicLinkTarget Method (FileInfo)
 

Gets the target of the specified symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static FileInfo GetSymbolicLinkTarget(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function GetSymbolicLinkTarget ( 
	file As FileInfo
) As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As FileInfo

returnValue = FileUtil.GetSymbolicLinkTarget(file)
```

**C++**<br />
``` C++
public:
static FileInfo^ GetSymbolicLinkTarget(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member GetSymbolicLinkTarget : 
        file : FileInfo -> FileInfo 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The (symbolic link) file.</dd></dl>

#### Return Value
Type: FileInfo<br />The target of the specified symbolic link.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetSymbolicLinkTarget">GetSymbolicLinkTarget Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />