# FileUtil.OpenInExplorer Method (String)
 

Opens the specified file in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void OpenInExplorer(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Sub OpenInExplorer ( 
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As StringFileUtil.OpenInExplorer(filepath)
```

**C++**<br />
``` C++
public:
static void OpenInExplorer(
	String^ filepath
)
```

**F#**<br />
``` F#
static member OpenInExplorer : 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>File or directory not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_OpenInExplorer">OpenInExplorer Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />