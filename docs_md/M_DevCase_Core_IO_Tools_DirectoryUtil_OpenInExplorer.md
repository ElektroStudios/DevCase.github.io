# DirectoryUtil.OpenInExplorer Method (DirectoryInfo)
 

Opens the specified directory in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void OpenInExplorer(
	DirectoryInfo directory
)
```

**VB**<br />
``` VB
Public Shared Sub OpenInExplorer ( 
	directory As DirectoryInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfoDirectoryUtil.OpenInExplorer(directory)
```

**C++**<br />
``` C++
public:
static void OpenInExplorer(
	DirectoryInfo^ directory
)
```

**F#**<br />
``` F#
static member OpenInExplorer : 
        directory : DirectoryInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The source directory.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_OpenInExplorer">OpenInExplorer Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />