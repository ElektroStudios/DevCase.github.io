# FileSystemUtil.ItemNameOrPathIsInvalid Method 
 

Determines whether the specified item is a name or a path, then, determines whether the item contains invalid windows name or path characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ItemNameOrPathIsInvalid(
	string itemNameOrPath
)
```

**VB**<br />
``` VB
Public Shared Function ItemNameOrPathIsInvalid ( 
	itemNameOrPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim itemNameOrPath As String
Dim returnValue As Boolean

returnValue = FileSystemUtil.ItemNameOrPathIsInvalid(itemNameOrPath)
```

**C++**<br />
``` C++
public:
static bool ItemNameOrPathIsInvalid(
	String^ itemNameOrPath
)
```

**F#**<br />
``` F#
static member ItemNameOrPathIsInvalid : 
        itemNameOrPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>itemNameOrPath</dt><dd>Type: System.String<br />The item name or path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if item contains invalid windows name characters, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />