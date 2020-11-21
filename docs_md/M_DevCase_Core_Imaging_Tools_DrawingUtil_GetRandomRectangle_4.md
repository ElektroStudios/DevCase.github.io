# DrawingUtil.GetRandomRectangle Method (Int32, Int32, Int32, Int32)
 

Gets a random Rectangle with a location between the specified maximum X and Y coordinates, and with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRandomRectangle(
	int xMax,
	int yMax,
	int wMax,
	int hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangle ( 
	xMax As Integer,
	yMax As Integer,
	wMax As Integer,
	hMax As Integer
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim xMax As Integer
Dim yMax As Integer
Dim wMax As Integer
Dim hMax As Integer
Dim returnValue As Rectangle

returnValue = DrawingUtil.GetRandomRectangle(xMax, 
	yMax, wMax, hMax)
```

**C++**<br />
``` C++
public:
static Rectangle GetRandomRectangle(
	int xMax, 
	int yMax, 
	int wMax, 
	int hMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangle : 
        xMax : int * 
        yMax : int * 
        wMax : int * 
        hMax : int -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>xMax</dt><dd>Type: System.Int32<br />The maximum X coordinate.</dd><dt>yMax</dt><dd>Type: System.Int32<br />The maximum Y coordinate.</dd><dt>wMax</dt><dd>Type: System.Int32<br />The maximum width.</dd><dt>hMax</dt><dd>Type: System.Int32<br />The maximum height.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangle">GetRandomRectangle Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />