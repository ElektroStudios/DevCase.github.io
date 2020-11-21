# DrawingUtil.PointRectangleToCenterOfRectangle Method 
 

Points the specified Rectangle to the center of another Rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point PointRectangleToCenterOfRectangle(
	Rectangle srcRect,
	Rectangle dstRect
)
```

**VB**<br />
``` VB
Public Shared Function PointRectangleToCenterOfRectangle ( 
	srcRect As Rectangle,
	dstRect As Rectangle
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim srcRect As Rectangle
Dim dstRect As Rectangle
Dim returnValue As Point

returnValue = DrawingUtil.PointRectangleToCenterOfRectangle(srcRect, 
	dstRect)
```

**C++**<br />
``` C++
public:
static Point PointRectangleToCenterOfRectangle(
	Rectangle srcRect, 
	Rectangle dstRect
)
```

**F#**<br />
``` F#
static member PointRectangleToCenterOfRectangle : 
        srcRect : Rectangle * 
        dstRect : Rectangle -> Point 

```


#### Parameters
&nbsp;<dl><dt>srcRect</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>dstRect</dt><dd>Type: System.Drawing.Rectangle<br />The target Rectangle.</dd></dl>

#### Return Value
Type: Point<br />The resulting coordinates.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />