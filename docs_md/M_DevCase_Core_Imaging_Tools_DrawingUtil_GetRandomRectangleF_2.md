# DrawingUtil.GetRandomRectangleF Method (PointF, SizeF)
 

Gets a random RectangleF with a location between the specified maximum X and Y coordinates, and with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static RectangleF GetRandomRectangleF(
	PointF locationMax,
	SizeF sizeMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangleF ( 
	locationMax As PointF,
	sizeMax As SizeF
) As RectangleF
```

**VB Usage**<br />
``` VB Usage
Dim locationMax As PointF
Dim sizeMax As SizeF
Dim returnValue As RectangleF

returnValue = DrawingUtil.GetRandomRectangleF(locationMax, 
	sizeMax)
```

**C++**<br />
``` C++
public:
static RectangleF GetRandomRectangleF(
	PointF locationMax, 
	SizeF sizeMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangleF : 
        locationMax : PointF * 
        sizeMax : SizeF -> RectangleF 

```


#### Parameters
&nbsp;<dl><dt>locationMax</dt><dd>Type: System.Drawing.PointF<br />A PointF that specifies the maximum X and Y coordinates.</dd><dt>sizeMax</dt><dd>Type: System.Drawing.SizeF<br />A SizeF that specifies the maximum width and height.</dd></dl>

#### Return Value
Type: RectangleF<br />The resulting RectangleF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangleF">GetRandomRectangleF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />