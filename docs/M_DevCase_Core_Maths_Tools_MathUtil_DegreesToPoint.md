# MathUtil.DegreesToPoint Method 
 

Calculates a point that is at an angle from the origin point (0 is to the right)

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PointF DegreesToPoint(
	float degrees,
	float radius,
	Point origin
)
```

**VB**<br />
``` VB
Public Shared Function DegreesToPoint ( 
	degrees As Single,
	radius As Single,
	origin As Point
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim degrees As Single
Dim radius As Single
Dim origin As Point
Dim returnValue As PointF

returnValue = MathUtil.DegreesToPoint(degrees, 
	radius, origin)
```

**C++**<br />
``` C++
public:
static PointF DegreesToPoint(
	float degrees, 
	float radius, 
	Point origin
)
```

**F#**<br />
``` F#
static member DegreesToPoint : 
        degrees : float32 * 
        radius : float32 * 
        origin : Point -> PointF 

```


#### Parameters
&nbsp;<dl><dt>degrees</dt><dd>Type: System.Single<br />The degrees.</dd><dt>radius</dt><dd>Type: System.Single<br />The radius.</dd><dt>origin</dt><dd>Type: System.Drawing.Point<br />The origin point.</dd></dl>

#### Return Value
Type: PointF<br />The resulting point.

## Remarks
Credits to: <a href="http://www.vcskicks.com/code-snippet/degree-to-xy.php" target="_blank">http://www.vcskicks.com/code-snippet/degree-to-xy.php</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />