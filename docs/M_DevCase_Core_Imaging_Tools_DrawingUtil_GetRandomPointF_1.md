# DrawingUtil.GetRandomPointF Method (PointF)
 

Gets a random PointF between the specified maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PointF GetRandomPointF(
	PointF pointMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomPointF ( 
	pointMax As PointF
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim pointMax As PointF
Dim returnValue As PointF

returnValue = DrawingUtil.GetRandomPointF(pointMax)
```

**C++**<br />
``` C++
public:
static PointF GetRandomPointF(
	PointF pointMax
)
```

**F#**<br />
``` F#
static member GetRandomPointF : 
        pointMax : PointF -> PointF 

```


#### Parameters
&nbsp;<dl><dt>pointMax</dt><dd>Type: System.Drawing.PointF<br />A PointF that specifies the maximum X and Y coordinates.</dd></dl>

#### Return Value
Type: PointF<br />The resulting PointF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomPointF">GetRandomPointF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />