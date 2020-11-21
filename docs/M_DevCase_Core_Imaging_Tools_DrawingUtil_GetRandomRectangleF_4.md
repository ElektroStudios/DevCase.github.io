# DrawingUtil.GetRandomRectangleF Method (Single, Single, Single, Single)
 

Gets a random RectangleF with a location between the specified maximum X and Y coordinates, and with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RectangleF GetRandomRectangleF(
	float xMax,
	float yMax,
	float wMax,
	float hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangleF ( 
	xMax As Single,
	yMax As Single,
	wMax As Single,
	hMax As Single
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim xMax As Single
Dim yMax As Single
Dim wMax As Single
Dim hMax As Single
Dim returnValue As RectangleF

returnValue = DrawingUtil.GetRandomRectangleF(xMax, 
	yMax, wMax, hMax)
```

**C++**<br />
``` C++
public:
static RectangleF GetRandomRectangleF(
	float xMax, 
	float yMax, 
	float wMax, 
	float hMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangleF : 
        xMax : float32 * 
        yMax : float32 * 
        wMax : float32 * 
        hMax : float32 -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>xMax</dt><dd>Type: System.Single<br />The maximum X coordinate.</dd><dt>yMax</dt><dd>Type: System.Single<br />The maximum Y coordinate.</dd><dt>wMax</dt><dd>Type: System.Single<br />The maximum width.</dd><dt>hMax</dt><dd>Type: System.Single<br />The maximum height.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangleF">GetRandomRectangleF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />