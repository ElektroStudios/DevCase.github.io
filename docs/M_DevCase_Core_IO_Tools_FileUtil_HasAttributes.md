# FileUtil.HasAttributes Method (FileInfo, FileAttributes)
 

Gets a value indicating whether a file contains the specified file-attribute(s).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HasAttributes(
	FileInfo file,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Function HasAttributes ( 
	file As FileInfo,
	attributes As FileAttributes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim attributes As FileAttributes
Dim returnValue As Boolean

returnValue = FileUtil.HasAttributes(file, 
	attributes)
```

**C++**<br />
``` C++
public:
static bool HasAttributes(
	FileInfo^ file, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member HasAttributes : 
        file : FileInfo * 
        attributes : FileAttributes -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The file attribute(s).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if file contains the file-attribute(s), `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Dim hasAttribute As Boolean = HasAttributes(file, FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_HasAttributes">HasAttributes Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />