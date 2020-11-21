# ShortcutFileInfo&nbsp;Implicit Conversion (ShortcutFileInfo to FileInfo)
 

Performs an implicit conversion from <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> to FileInfo.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator FileInfo (
	ShortcutFileInfo file
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	file As ShortcutFileInfo
) As FileInfo
```

**VB Usage**<br />
``` VB Usage
Dim input As ShortcutFileInfo
Dim output As FileInfo

output = CType(input, FileInfo)
```

**C++**<br />
``` C++
static implicit operator FileInfo^ (
	ShortcutFileInfo^ file
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: <a href="T_DevCase_Core_IO_ShortcutFileInfo">DevCase.Core.IO.ShortcutFileInfo</a><br />The <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a>.</dd></dl>

#### Return Value
Type: FileInfo<br />The resulting FileInfo.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="Overload_DevCase_Core_IO_ShortcutFileInfo_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />