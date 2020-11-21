# DrawingUtil.PointRectangleToCenterOfControl Method 
 

Points the specified Rectangle to the center of a Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point PointRectangleToCenterOfControl(
	Rectangle rc,
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function PointRectangleToCenterOfControl ( 
	rc As Rectangle,
	ctrl As Control
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim rc As Rectangle
Dim ctrl As Control
Dim returnValue As Point

returnValue = DrawingUtil.PointRectangleToCenterOfControl(rc, 
	ctrl)
```

**C++**<br />
``` C++
public:
static Point PointRectangleToCenterOfControl(
	Rectangle rc, 
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member PointRectangleToCenterOfControl : 
        rc : Rectangle * 
        ctrl : Control -> Point 

```


#### Parameters
&nbsp;<dl><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The target Control.</dd></dl>

#### Return Value
Type: Point<br />The resulting coordinates.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />