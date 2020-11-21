# DrawingUtil.GetRandomRectangleF Method (PointF)
 

Gets a random RectangleF with a location between the specified maximum X and Y coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RectangleF GetRandomRectangleF(
	PointF locationMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangleF ( 
	locationMax As PointF
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim locationMax As PointF
Dim returnValue As RectangleF

returnValue = DrawingUtil.GetRandomRectangleF(locationMax)
```

**C++**<br />
``` C++
public:
static RectangleF GetRandomRectangleF(
	PointF locationMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangleF : 
        locationMax : PointF -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>locationMax</dt><dd>Type: System.Drawing.PointF<br />A PointF that specifies the maximum X and Y coordinates.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangleF">GetRandomRectangleF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />