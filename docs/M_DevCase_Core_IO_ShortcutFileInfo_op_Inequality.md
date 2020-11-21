# ShortcutFileInfo.Inequality Operator 
 

Determines whether the specified <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> instances are not equal.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator !=(
	ShortcutFileInfo first,
	ShortcutFileInfo second
)
```

**VB**<br />
``` VB
Public Shared Operator <> ( 
	first As ShortcutFileInfo,
	second As ShortcutFileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim first As ShortcutFileInfo
Dim second As ShortcutFileInfo
Dim returnValue As Boolean

returnValue = (first <> second)
```

**C++**<br />
``` C++
public:
static bool operator !=(
	ShortcutFileInfo^ first, 
	ShortcutFileInfo^ second
)
```

**F#**<br />
``` F#
static let inline (<>)
        first : ShortcutFileInfo * 
        second : ShortcutFileInfo  : bool
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Core_IO_ShortcutFileInfo">DevCase.Core.IO.ShortcutFileInfo</a><br />The first <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> to compare.</dd><dt>second</dt><dd>Type: <a href="T_DevCase_Core_IO_ShortcutFileInfo">DevCase.Core.IO.ShortcutFileInfo</a><br />The second <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> to compare.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> instances are not equal; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />