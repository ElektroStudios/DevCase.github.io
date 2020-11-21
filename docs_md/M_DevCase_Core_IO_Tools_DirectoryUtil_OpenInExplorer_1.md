# DirectoryUtil.OpenInExplorer Method (String)
 

Opens the specified directory in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void OpenInExplorer(
	string directoryPath
)
```

**VB**<br />
``` VB
Public Shared Sub OpenInExplorer ( 
	directoryPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim directoryPath As StringDirectoryUtil.OpenInExplorer(directoryPath)
```

**C++**<br />
``` C++
public:
static void OpenInExplorer(
	String^ directoryPath
)
```

**F#**<br />
``` F#
static member OpenInExplorer : 
        directoryPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>directoryPath</dt><dd>Type: System.String<br />The directory path.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_OpenInExplorer">OpenInExplorer Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />