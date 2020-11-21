# DrawingUtil.GetRandomPointF Method (Single, Single, Single, Single)
 

Gets a random PointF between the specified minimum and maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PointF GetRandomPointF(
	float xMin,
	float xMax,
	float yMin,
	float yMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomPointF ( 
	xMin As Single,
	xMax As Single,
	yMin As Single,
	yMax As Single
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim xMin As Single
Dim xMax As Single
Dim yMin As Single
Dim yMax As Single
Dim returnValue As PointF

returnValue = DrawingUtil.GetRandomPointF(xMin, 
	xMax, yMin, yMax)
```

**C++**<br />
``` C++
public:
static PointF GetRandomPointF(
	float xMin, 
	float xMax, 
	float yMin, 
	float yMax
)
```

**F#**<br />
``` F#
static member GetRandomPointF : 
        xMin : float32 * 
        xMax : float32 * 
        yMin : float32 * 
        yMax : float32 -> PointF 

```


#### Parameters
&nbsp;<dl><dt>xMin</dt><dd>Type: System.Single<br />The minimum X coordinate.</dd><dt>xMax</dt><dd>Type: System.Single<br />The maximum X coordinate.</dd><dt>yMin</dt><dd>Type: System.Single<br />The minimum Y coordinate.</dd><dt>yMax</dt><dd>Type: System.Single<br />The maximum Y coordinate.</dd></dl>

#### Return Value
Type: PointF<br />The resulting PointF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomPointF">GetRandomPointF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />