# DrawingUtil.FillRectangleOnScreen Method 
 

Draw and fill a rectangle on the specified device screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void FillRectangleOnScreen(
	Screen screen,
	Rectangle rc,
	Color color
)
```

**VB**<br />
``` VB
Public Shared Sub FillRectangleOnScreen ( 
	screen As Screen,
	rc As Rectangle,
	color As Color
)
```

**VB Usage**<br />
``` VB Usage
Dim screen As Screen
Dim rc As Rectangle
Dim color As ColorDrawingUtil.FillRectangleOnScreen(screen, 
	rc, color)
```

**C++**<br />
``` C++
public:
static void FillRectangleOnScreen(
	Screen^ screen, 
	Rectangle rc, 
	Color color
)
```

**F#**<br />
``` F#
static member FillRectangleOnScreen : 
        screen : Screen * 
        rc : Rectangle * 
        color : Color -> unit 

```


#### Parameters
&nbsp;<dl><dt>screen</dt><dd>Type: System.Windows.Forms.Screen<br />The device screen where to draw the rectangle.</dd><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that represents the size and position of the rectangle to draw.</dd><dt>color</dt><dd>Type: System.Drawing.Color<br />The color of the rectangle.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scr As Screen = Screen.PrimaryScreen
Dim rc As Rectangle = scr.Bounds

DrawRectangleOnScreen(scr, rc, Color.Red)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />