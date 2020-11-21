# MouseUtil.Move Method (Point)
 

Moves the current mouse position by the specified offset.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Move(
	Point offset
)
```

**VB**<br />
``` VB
Public Shared Sub Move ( 
	offset As Point
)
```

**VB Usage**<br />
``` VB Usage
Dim offset As PointMouseUtil.Move(offset)
```

**C++**<br />
``` C++
public:
static void Move(
	Point offset
)
```

**F#**<br />
``` F#
static member Move : 
        offset : Point -> unit 

```


#### Parameters
&nbsp;<dl><dt>offset</dt><dd>Type: System.Drawing.Point<br />The offset point, in coordinates. You can use positive and negative values.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Move(New Point(x:=+5, y:=-5))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_MouseUtil">MouseUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_MouseUtil_Move">Move Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />