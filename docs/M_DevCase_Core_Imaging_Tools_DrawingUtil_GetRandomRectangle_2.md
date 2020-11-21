# DrawingUtil.GetRandomRectangle Method (Point, Size)
 

Gets a random Rectangle with a location between the specified maximum X and Y coordinates, and with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRandomRectangle(
	Point locationMax,
	Size sizeMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangle ( 
	locationMax As Point,
	sizeMax As Size
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim locationMax As Point
Dim sizeMax As Size
Dim returnValue As Rectangle

returnValue = DrawingUtil.GetRandomRectangle(locationMax, 
	sizeMax)
```

**C++**<br />
``` C++
public:
static Rectangle GetRandomRectangle(
	Point locationMax, 
	Size sizeMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangle : 
        locationMax : Point * 
        sizeMax : Size -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>locationMax</dt><dd>Type: System.Drawing.Point<br />A Point that specifies the maximum X and Y coordinates.</dd><dt>sizeMax</dt><dd>Type: System.Drawing.Size<br />A Size that specifies the maximum width and height.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangle">GetRandomRectangle Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />