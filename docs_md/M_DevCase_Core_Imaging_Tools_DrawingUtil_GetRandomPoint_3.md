# DrawingUtil.GetRandomPoint Method (Int32, Int32, Int32, Int32)
 

Gets a random Point between the specified minimum and maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point GetRandomPoint(
	int xMin,
	int xMax,
	int yMin,
	int yMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomPoint ( 
	xMin As Integer,
	xMax As Integer,
	yMin As Integer,
	yMax As Integer
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim xMin As Integer
Dim xMax As Integer
Dim yMin As Integer
Dim yMax As Integer
Dim returnValue As Point

returnValue = DrawingUtil.GetRandomPoint(xMin, 
	xMax, yMin, yMax)
```

**C++**<br />
``` C++
public:
static Point GetRandomPoint(
	int xMin, 
	int xMax, 
	int yMin, 
	int yMax
)
```

**F#**<br />
``` F#
static member GetRandomPoint : 
        xMin : int * 
        xMax : int * 
        yMin : int * 
        yMax : int -> Point 

```


#### Parameters
&nbsp;<dl><dt>xMin</dt><dd>Type: System.Int32<br />The minimum X coordinate.</dd><dt>xMax</dt><dd>Type: System.Int32<br />The maximum X coordinate.</dd><dt>yMin</dt><dd>Type: System.Int32<br />The minimum Y coordinate.</dd><dt>yMax</dt><dd>Type: System.Int32<br />The maximum Y coordinate.</dd></dl>

#### Return Value
Type: Point<br />The resulting Point.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomPoint">GetRandomPoint Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />