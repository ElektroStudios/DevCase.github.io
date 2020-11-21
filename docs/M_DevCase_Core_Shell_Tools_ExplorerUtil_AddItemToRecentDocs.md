# ExplorerUtil.AddItemToRecentDocs Method 
 

Adds an item into the Windows recent docs (MRU) list.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddItemToRecentDocs(
	string filePath
)
```

**VB**<br />
``` VB
Public Shared Sub AddItemToRecentDocs ( 
	filePath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As StringExplorerUtil.AddItemToRecentDocs(filePath)
```

**C++**<br />
``` C++
public:
static void AddItemToRecentDocs(
	String^ filePath
)
```

**F#**<br />
``` F#
static member AddItemToRecentDocs : 
        filePath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The file path.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>filePath</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/gg537735%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/gg537735%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ExplorerUtil">ExplorerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />