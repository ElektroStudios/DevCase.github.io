# DrawingUtil.PointRectangleToCenterOfScreen Method 
 

Points the specified Rectangle to the center of a screen Screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point PointRectangleToCenterOfScreen(
	Rectangle rc,
	Screen scr
)
```

**VB**<br />
``` VB
Public Shared Function PointRectangleToCenterOfScreen ( 
	rc As Rectangle,
	scr As Screen
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim rc As Rectangle
Dim scr As Screen
Dim returnValue As Point

returnValue = DrawingUtil.PointRectangleToCenterOfScreen(rc, 
	scr)
```

**C++**<br />
``` C++
public:
static Point PointRectangleToCenterOfScreen(
	Rectangle rc, 
	Screen^ scr
)
```

**F#**<br />
``` F#
static member PointRectangleToCenterOfScreen : 
        rc : Rectangle * 
        scr : Screen -> Point 

```


#### Parameters
&nbsp;<dl><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>scr</dt><dd>Type: System.Windows.Forms.Screen<br />The target Screen.</dd></dl>

#### Return Value
Type: Point<br />The resulting coordinates.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />