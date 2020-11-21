# DrawingUtil.PointRectangleFToCenterOfRectangleF Method 
 

Points the specified RectangleF to the center of another RectangleF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PointF PointRectangleFToCenterOfRectangleF(
	RectangleF srcRect,
	RectangleF dstRect
)
```

**VB**<br />
``` VB
Public Shared Function PointRectangleFToCenterOfRectangleF ( 
	srcRect As RectangleF,
	dstRect As RectangleF
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim srcRect As RectangleF
Dim dstRect As RectangleF
Dim returnValue As PointF

returnValue = DrawingUtil.PointRectangleFToCenterOfRectangleF(srcRect, 
	dstRect)
```

**C++**<br />
``` C++
public:
static PointF PointRectangleFToCenterOfRectangleF(
	RectangleF srcRect, 
	RectangleF dstRect
)
```

**F#**<br />
``` F#
static member PointRectangleFToCenterOfRectangleF : 
        srcRect : RectangleF * 
        dstRect : RectangleF -> PointF 

```


#### Parameters
&nbsp;<dl><dt>srcRect</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd><dt>dstRect</dt><dd>Type: System.Drawing.RectangleF<br />The target RectangleF.</dd></dl>

#### Return Value
Type: PointF<br />The resulting coordinates.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />