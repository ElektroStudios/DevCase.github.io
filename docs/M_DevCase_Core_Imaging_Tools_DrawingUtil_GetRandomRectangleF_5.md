# DrawingUtil.GetRandomRectangleF Method (Single, Single, Single, Single, Single, Single, Single, Single)
 

Gets a random RectangleF with a location between the specified minimum and maximum X and Y coordinates, and with a size between the specified minimum and maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RectangleF GetRandomRectangleF(
	float xMin,
	float xMax,
	float yMin,
	float yMax,
	float wMin,
	float wMax,
	float hMin,
	float hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangleF ( 
	xMin As Single,
	xMax As Single,
	yMin As Single,
	yMax As Single,
	wMin As Single,
	wMax As Single,
	hMin As Single,
	hMax As Single
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim xMin As Single
Dim xMax As Single
Dim yMin As Single
Dim yMax As Single
Dim wMin As Single
Dim wMax As Single
Dim hMin As Single
Dim hMax As Single
Dim returnValue As RectangleF

returnValue = DrawingUtil.GetRandomRectangleF(xMin, 
	xMax, yMin, yMax, wMin, wMax, hMin, 
	hMax)
```

**C++**<br />
``` C++
public:
static RectangleF GetRandomRectangleF(
	float xMin, 
	float xMax, 
	float yMin, 
	float yMax, 
	float wMin, 
	float wMax, 
	float hMin, 
	float hMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangleF : 
        xMin : float32 * 
        xMax : float32 * 
        yMin : float32 * 
        yMax : float32 * 
        wMin : float32 * 
        wMax : float32 * 
        hMin : float32 * 
        hMax : float32 -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>xMin</dt><dd>Type: System.Single<br />The minimum X coordinate.</dd><dt>xMax</dt><dd>Type: System.Single<br />The maximum X coordinate.</dd><dt>yMin</dt><dd>Type: System.Single<br />The minimum Y coordinate.</dd><dt>yMax</dt><dd>Type: System.Single<br />The maximum Y coordinate.</dd><dt>wMin</dt><dd>Type: System.Single<br />The minimum width.</dd><dt>wMax</dt><dd>Type: System.Single<br />The maximum width.</dd><dt>hMin</dt><dd>Type: System.Single<br />The minimum height.</dd><dt>hMax</dt><dd>Type: System.Single<br />The maximum height.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangleF">GetRandomRectangleF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />