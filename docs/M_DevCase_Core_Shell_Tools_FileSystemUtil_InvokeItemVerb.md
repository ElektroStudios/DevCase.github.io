# FileSystemUtil.InvokeItemVerb Method (String, ItemVerbs)
 

Invokes an item verb on the specified file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InvokeItemVerb(
	string itemPath,
	ItemVerbs verb
)
```

**VB**<br />
``` VB
Public Shared Sub InvokeItemVerb ( 
	itemPath As String,
	verb As ItemVerbs
)
```

**VB Usage**<br />
``` VB Usage
Dim itemPath As String
Dim verb As ItemVerbsFileSystemUtil.InvokeItemVerb(itemPath, verb)
```

**C++**<br />
``` C++
public:
static void InvokeItemVerb(
	String^ itemPath, 
	ItemVerbs verb
)
```

**F#**<br />
``` F#
static member InvokeItemVerb : 
        itemPath : string * 
        verb : ItemVerbs -> unit 

```


#### Parameters
&nbsp;<dl><dt>itemPath</dt><dd>Type: System.String<br />The item path.</dd><dt>verb</dt><dd>Type: <a href="T_DevCase_Core_Shell_ItemVerbs">DevCase.Core.Shell.ItemVerbs</a><br />The verb.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_FileSystemUtil_InvokeItemVerb">InvokeItemVerb Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />