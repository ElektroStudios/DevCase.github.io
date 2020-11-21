# ShortcutFileInfo&nbsp;Implicit Conversion (FileInfo to ShortcutFileInfo)
 

Performs an implicit conversion from FileInfo to <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator ShortcutFileInfo (
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	file As FileInfo
) As ShortcutFileInfo
```

**VB Usage**<br />
``` VB Usage
Dim input As FileInfo
Dim output As ShortcutFileInfo

output = CType(input, ShortcutFileInfo)
```

**C++**<br />
``` C++
static implicit operator ShortcutFileInfo^ (
	FileInfo^ file
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The FileInfo.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a><br />The resulting <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="Overload_DevCase_Core_IO_ShortcutFileInfo_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />