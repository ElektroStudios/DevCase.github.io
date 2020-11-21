# DrawingUtil.GetRandomRectangle Method (Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)
 

Gets a random Rectangle with a location between the specified minimum and maximum X and Y coordinates, and with a size between the specified minimum and maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRandomRectangle(
	int xMin,
	int xMax,
	int yMin,
	int yMax,
	int wMin,
	int wMax,
	int hMin,
	int hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangle ( 
	xMin As Integer,
	xMax As Integer,
	yMin As Integer,
	yMax As Integer,
	wMin As Integer,
	wMax As Integer,
	hMin As Integer,
	hMax As Integer
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim xMin As Integer
Dim xMax As Integer
Dim yMin As Integer
Dim yMax As Integer
Dim wMin As Integer
Dim wMax As Integer
Dim hMin As Integer
Dim hMax As Integer
Dim returnValue As Rectangle

returnValue = DrawingUtil.GetRandomRectangle(xMin, 
	xMax, yMin, yMax, wMin, wMax, hMin, 
	hMax)
```

**C++**<br />
``` C++
public:
static Rectangle GetRandomRectangle(
	int xMin, 
	int xMax, 
	int yMin, 
	int yMax, 
	int wMin, 
	int wMax, 
	int hMin, 
	int hMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangle : 
        xMin : int * 
        xMax : int * 
        yMin : int * 
        yMax : int * 
        wMin : int * 
        wMax : int * 
        hMin : int * 
        hMax : int -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>xMin</dt><dd>Type: System.Int32<br />The minimum X coordinate.</dd><dt>xMax</dt><dd>Type: System.Int32<br />The maximum X coordinate.</dd><dt>yMin</dt><dd>Type: System.Int32<br />The minimum Y coordinate.</dd><dt>yMax</dt><dd>Type: System.Int32<br />The maximum Y coordinate.</dd><dt>wMin</dt><dd>Type: System.Int32<br />The minimum width.</dd><dt>wMax</dt><dd>Type: System.Int32<br />The maximum width.</dd><dt>hMin</dt><dd>Type: System.Int32<br />The minimum height.</dd><dt>hMax</dt><dd>Type: System.Int32<br />The maximum height.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangle">GetRandomRectangle Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />