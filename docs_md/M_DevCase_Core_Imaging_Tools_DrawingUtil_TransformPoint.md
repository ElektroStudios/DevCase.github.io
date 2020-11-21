# DrawingUtil.TransformPoint Method (Rectangle, Rectangle, Point)
 

Transforms a Point from a coordinate space relative to one Rectangle to a coordinate space relative to another Rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point TransformPoint(
	Rectangle source,
	Rectangle target,
	Point pt
)
```

**VB**<br />
``` VB
Public Shared Function TransformPoint ( 
	source As Rectangle,
	target As Rectangle,
	pt As Point
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim source As Rectangle
Dim target As Rectangle
Dim pt As Point
Dim returnValue As Point

returnValue = DrawingUtil.TransformPoint(source, 
	target, pt)
```

**C++**<br />
``` C++
public:
static Point TransformPoint(
	Rectangle source, 
	Rectangle target, 
	Point pt
)
```

**F#**<br />
``` F#
static member TransformPoint : 
        source : Rectangle * 
        target : Rectangle * 
        pt : Point -> Point 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Drawing.Rectangle<br />The source Rectangle.</dd><dt>target</dt><dd>Type: System.Drawing.Rectangle<br />The destination Rectangle.</dd><dt>pt</dt><dd>Type: System.Drawing.Point<br />The source Point.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_TransformPoint">TransformPoint Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />