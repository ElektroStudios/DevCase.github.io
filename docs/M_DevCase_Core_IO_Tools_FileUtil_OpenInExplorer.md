# FileUtil.OpenInExplorer Method (FileInfo)
 

Opens the specified file in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void OpenInExplorer(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Sub OpenInExplorer ( 
	file As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfoFileUtil.OpenInExplorer(file)
```

**C++**<br />
``` C++
public:
static void OpenInExplorer(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member OpenInExplorer : 
        file : FileInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_OpenInExplorer">OpenInExplorer Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />