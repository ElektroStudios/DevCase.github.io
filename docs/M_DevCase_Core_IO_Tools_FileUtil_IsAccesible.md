# FileUtil.IsAccesible Method (FileInfo, FileAccess)
 

Determines whether the specified file is accesible in the context of reading or writting to the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAccesible(
	FileInfo file,
	FileAccess fileAccess
)
```

**VB**<br />
``` VB
Public Shared Function IsAccesible ( 
	file As FileInfo,
	fileAccess As FileAccess
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim fileAccess As FileAccess
Dim returnValue As Boolean

returnValue = FileUtil.IsAccesible(file, 
	fileAccess)
```

**C++**<br />
``` C++
public:
static bool IsAccesible(
	FileInfo^ file, 
	FileAccess fileAccess
)
```

**F#**<br />
``` F#
static member IsAccesible : 
        file : FileInfo * 
        fileAccess : FileAccess -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>fileAccess</dt><dd>Type: System.IO.FileAccess<br />The file access to check.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if file is accesible; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Dim isAccesible As Boolean = IsAccesible(file, FileAccess.Read)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_IsAccesible">IsAccesible Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />