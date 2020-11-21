# DrawingUtil.GetRandomRectangle Method (Point)
 

Gets a random Rectangle with a location between the specified maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRandomRectangle(
	Point locationMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangle ( 
	locationMax As Point
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim locationMax As Point
Dim returnValue As Rectangle

returnValue = DrawingUtil.GetRandomRectangle(locationMax)
```

**C++**<br />
``` C++
public:
static Rectangle GetRandomRectangle(
	Point locationMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangle : 
        locationMax : Point -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>locationMax</dt><dd>Type: System.Drawing.Point<br />A Point that specifies the maximum X and Y coordinates.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangle">GetRandomRectangle Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />