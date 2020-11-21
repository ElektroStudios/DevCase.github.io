# DrawingUtil.GetRandomPoint Method (Point)
 

Gets a random Point between the specified maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point GetRandomPoint(
	Point pointMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomPoint ( 
	pointMax As Point
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim pointMax As Point
Dim returnValue As Point

returnValue = DrawingUtil.GetRandomPoint(pointMax)
```

**C++**<br />
``` C++
public:
static Point GetRandomPoint(
	Point pointMax
)
```

**F#**<br />
``` F#
static member GetRandomPoint : 
        pointMax : Point -> Point 

```


#### Parameters
&nbsp;<dl><dt>pointMax</dt><dd>Type: System.Drawing.Point<br />A Point that specifies the maximum X and Y coordinates.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomPoint">GetRandomPoint Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />