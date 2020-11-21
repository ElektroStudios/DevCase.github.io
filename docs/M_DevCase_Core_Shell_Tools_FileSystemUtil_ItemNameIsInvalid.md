# FileSystemUtil.ItemNameIsInvalid Method 
 

Determines whether a directory name or file name contains invalid windows path characters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ItemNameIsInvalid(
	string itemName
)
```

**VB**<br />
``` VB
Public Shared Function ItemNameIsInvalid ( 
	itemName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim itemName As String
Dim returnValue As Boolean

returnValue = FileSystemUtil.ItemNameIsInvalid(itemName)
```

**C++**<br />
``` C++
public:
static bool ItemNameIsInvalid(
	String^ itemName
)
```

**F#**<br />
``` F#
static member ItemNameIsInvalid : 
        itemName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>itemName</dt><dd>Type: System.String<br />The item name.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if item contains invalid windows name characters, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />