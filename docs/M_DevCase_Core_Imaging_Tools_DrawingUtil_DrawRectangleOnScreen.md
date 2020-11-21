# DrawingUtil.DrawRectangleOnScreen Method (Screen, Rectangle, Color)
 

Draw a rectangle on the specified device screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DrawRectangleOnScreen(
	Screen screen,
	Rectangle rc,
	Color borderColor
)
```

**VB**<br />
``` VB
Public Shared Sub DrawRectangleOnScreen ( 
	screen As Screen,
	rc As Rectangle,
	borderColor As Color
)
```

**VB Usage**<br />
``` VB Usage
Dim screen As Screen
Dim rc As Rectangle
Dim borderColor As ColorDrawingUtil.DrawRectangleOnScreen(screen, 
	rc, borderColor)
```

**C++**<br />
``` C++
public:
static void DrawRectangleOnScreen(
	Screen^ screen, 
	Rectangle rc, 
	Color borderColor
)
```

**F#**<br />
``` F#
static member DrawRectangleOnScreen : 
        screen : Screen * 
        rc : Rectangle * 
        borderColor : Color -> unit 

```


#### Parameters
&nbsp;<dl><dt>screen</dt><dd>Type: System.Windows.Forms.Screen<br />The device screen where to draw the rectangle.</dd><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that represents the size and position of the rectangle to draw.</dd><dt>borderColor</dt><dd>Type: System.Drawing.Color<br />The border color of the rectangle.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scr As Screen = Screen.PrimaryScreen
Dim rc As New Rectangle(New Point(0, 0), New Size(100, 100))

DrawRectangleOnScreen(scr, rc, Color.Red)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_DrawRectangleOnScreen">DrawRectangleOnScreen Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />