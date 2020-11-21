# DrawingUtil.PointRectangleToCenterOfForm Method 
 

Points the specified Rectangle to the center of a Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point PointRectangleToCenterOfForm(
	Rectangle rc,
	Form form
)
```

**VB**<br />
``` VB
Public Shared Function PointRectangleToCenterOfForm ( 
	rc As Rectangle,
	form As Form
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim rc As Rectangle
Dim form As Form
Dim returnValue As Point

returnValue = DrawingUtil.PointRectangleToCenterOfForm(rc, 
	form)
```

**C++**<br />
``` C++
public:
static Point PointRectangleToCenterOfForm(
	Rectangle rc, 
	Form^ form
)
```

**F#**<br />
``` F#
static member PointRectangleToCenterOfForm : 
        rc : Rectangle * 
        form : Form -> Point 

```


#### Parameters
&nbsp;<dl><dt>rc</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The target Form.</dd></dl>

#### Return Value
Type: Point<br />The resulting coordinates.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />