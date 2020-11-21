# FileSystemUtil.ItemPathIsInvalid Method 
 

Determines whether a directory path or a file path contains invalid windows path characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ItemPathIsInvalid(
	string itemPath
)
```

**VB**<br />
``` VB
Public Shared Function ItemPathIsInvalid ( 
	itemPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim itemPath As String
Dim returnValue As Boolean

returnValue = FileSystemUtil.ItemPathIsInvalid(itemPath)
```

**C++**<br />
``` C++
public:
static bool ItemPathIsInvalid(
	String^ itemPath
)
```

**F#**<br />
``` F#
static member ItemPathIsInvalid : 
        itemPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>itemPath</dt><dd>Type: System.String<br />The item path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if item contains invalid windows path characters, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />