# MouseUtil.Move Method (Int32, Int32)
 

Moves the current mouse position by the specified offset.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Move(
	int x,
	int y
)
```

**VB**<br />
``` VB
Public Shared Sub Move ( 
	x As Integer,
	y As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer

MouseUtil.Move(x, y)
```

**C++**<br />
``` C++
public:
static void Move(
	int x, 
	int y
)
```

**F#**<br />
``` F#
static member Move : 
        x : int * 
        y : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The 'X' coordinate offset.</dd><dt>y</dt><dd>Type: System.Int32<br />The 'Y' coordinate offset.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Move(x:=5, y:=-5)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_MouseUtil">MouseUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_MouseUtil_Move">Move Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />