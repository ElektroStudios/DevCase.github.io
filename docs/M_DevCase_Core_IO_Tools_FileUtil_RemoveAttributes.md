# FileUtil.RemoveAttributes Method (FileInfo, FileAttributes)
 

Removes file-attribute(s) from the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveAttributes(
	FileInfo file,
	FileAttributes attributes
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveAttributes ( 
	file As FileInfo,
	attributes As FileAttributes
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim attributes As FileAttributesFileUtil.RemoveAttributes(file, attributes)
```

**C++**<br />
``` C++
public:
static void RemoveAttributes(
	FileInfo^ file, 
	FileAttributes attributes
)
```

**F#**<br />
``` F#
static member RemoveAttributes : 
        file : FileInfo * 
        attributes : FileAttributes -> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>attributes</dt><dd>Type: System.IO.FileAttributes<br />The file attribute(s) to remove.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
RemoveAttributes(file, FileAttributes.Hidden Or FileAttributes.ReadOnly)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_RemoveAttributes">RemoveAttributes Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />