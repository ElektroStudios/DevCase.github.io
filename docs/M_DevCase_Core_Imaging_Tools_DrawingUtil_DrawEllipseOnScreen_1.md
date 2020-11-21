# DrawingUtil.DrawEllipseOnScreen Method (Screen, Rectangle, Color, Int32)
 

Draw a ellipse on the specified device screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DrawEllipseOnScreen(
	Screen screen,
	Rectangle rc,
	Color borderColor,
	int borderWidth
)
```

**VB**<br />
``` VB
Public Shared Sub DrawEllipseOnScreen ( 
	screen As Screen,
	rc As Rectangle,
	borderColor As Color,
	borderWidth As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim screen As Screen
Dim rc As Rectangle
Dim borderColor As Color
Dim borderWidth As Integer

DrawingUtil.DrawEllipseOnScreen(screen, 
	rc, borderColor, borderWidth)
```

**C++**<br />
``` C++
public:
static void DrawEllipseOnScreen(
	Screen^ screen, 
	Rectangle rc, 
	Color borderColor, 
	int borderWidth
)
```

**F#**<br />
``` F#
static member DrawEllipseOnScreen : 
        screen : Screen * 
        rc : Rectangle * 
        borderColor : Color * 
        borderWidth : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>screen</dt><dd>Type: System.Windows.Forms.Screen<br />The device screen where to draw the ellipse.</dd><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that represents the size and position of the ellipse to draw.</dd><dt>borderColor</dt><dd>Type: System.Drawing.Color<br />The border color of the ellipse.</dd><dt>borderWidth</dt><dd>Type: System.Int32<br />The border width of the ellipse.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scr As Screen = Screen.PrimaryScreen
Dim rc As New Rectangle(New Point(0, 0), New Size(100, 100))

DrawEllipseOnScreen(scr, rc, Color.Red, 4)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_DrawEllipseOnScreen">DrawEllipseOnScreen Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />