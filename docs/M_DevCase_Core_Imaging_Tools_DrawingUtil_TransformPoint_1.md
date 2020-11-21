# DrawingUtil.TransformPoint Method (RectangleF, RectangleF, PointF)
 

Transforms a PointF from a coordinate space relative to one RectangleF to a coordinate space relative to another RectangleF.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PointF TransformPoint(
	RectangleF source,
	RectangleF target,
	PointF pt
)
```

**VB**<br />
``` VB
Public Shared Function TransformPoint ( 
	source As RectangleF,
	target As RectangleF,
	pt As PointF
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim source As RectangleF
Dim target As RectangleF
Dim pt As PointF
Dim returnValue As PointF

returnValue = DrawingUtil.TransformPoint(source, 
	target, pt)
```

**C++**<br />
``` C++
public:
static PointF TransformPoint(
	RectangleF source, 
	RectangleF target, 
	PointF pt
)
```

**F#**<br />
``` F#
static member TransformPoint : 
        source : RectangleF * 
        target : RectangleF * 
        pt : PointF -> PointF 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Drawing.RectangleF<br />The source RectangleF.</dd><dt>target</dt><dd>Type: System.Drawing.RectangleF<br />The destination RectangleF.</dd><dt>pt</dt><dd>Type: System.Drawing.PointF<br />The source PointF.</dd></dl>

#### Return Value
Type: PointF<br />The resulting PointF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_TransformPoint">TransformPoint Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />