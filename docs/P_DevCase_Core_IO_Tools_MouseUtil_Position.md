# MouseUtil.Position Property 
 

Gets or sets the mouse position on the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point Position { get; set; }
```

**VB**<br />
``` VB
Public Shared Property Position As Point
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Point

value = MouseUtil.Position

MouseUtil.Position = value
```

**C++**<br />
``` C++
public:
static property Point Position {
	Point get ();
	void set (Point value);
}
```

**F#**<br />
``` F#
static member Position : Point with get, set

```


#### Property Value
Type: Point<br />The mouse position.

## Examples
This is a code example. 
**VB**<br />
``` VB
Position = New Point(x:=100, y:=500)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_MouseUtil">MouseUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />