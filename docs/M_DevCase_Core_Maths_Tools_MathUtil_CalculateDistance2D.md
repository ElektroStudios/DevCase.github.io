# MathUtil.CalculateDistance2D Method 
 

Calculates the distance between two points in two dimensions in the coordinate system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double CalculateDistance2D(
	PointF pointA,
	PointF pointB
)
```

**VB**<br />
``` VB
Public Shared Function CalculateDistance2D ( 
	pointA As PointF,
	pointB As PointF
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim pointA As PointF
Dim pointB As PointF
Dim returnValue As Double

returnValue = MathUtil.CalculateDistance2D(pointA, 
	pointB)
```

**C++**<br />
``` C++
public:
static double CalculateDistance2D(
	PointF pointA, 
	PointF pointB
)
```

**F#**<br />
``` F#
static member CalculateDistance2D : 
        pointA : PointF * 
        pointB : PointF -> float 

```


#### Parameters
&nbsp;<dl><dt>pointA</dt><dd>Type: System.Drawing.PointF<br />The first point.</dd><dt>pointB</dt><dd>Type: System.Drawing.PointF<br />The second point.</dd></dl>

#### Return Value
Type: Double<br />The resulting distance.

## Remarks
Pythagorean theorem: <a href="http://en.wikipedia.org/wiki/Pythagorean_theorem" target="_blank">http://en.wikipedia.org/wiki/Pythagorean_theorem</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim distance As Double = CalculateDistance2D(New PointF(1, 1), New PointF(2, 2))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />