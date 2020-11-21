# FileSystemUtil.GetItemVerbs Method 
 

Gets the available item verbs of the specified file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<FolderItemVerb> GetItemVerbs(
	string itemPath
)
```

**VB**<br />
``` VB
Public Shared Function GetItemVerbs ( 
	itemPath As String
) As IEnumerable(Of FolderItemVerb)
```

**VB Usage**<br />
``` VB Usage
Dim itemPath As String
Dim returnValue As IEnumerable(Of FolderItemVerb)

returnValue = FileSystemUtil.GetItemVerbs(itemPath)
```

**C++**<br />
``` C++
public:
static IEnumerable<FolderItemVerb^>^ GetItemVerbs(
	String^ itemPath
)
```

**F#**<br />
``` F#
static member GetItemVerbs : 
        itemPath : string -> IEnumerable<FolderItemVerb> 

```


#### Parameters
&nbsp;<dl><dt>itemPath</dt><dd>Type: System.String<br />The item path.</dd></dl>

#### Return Value
Type: IEnumerable(FolderItemVerb)<br />An IEnumerable(T) containing the available item verbs.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />