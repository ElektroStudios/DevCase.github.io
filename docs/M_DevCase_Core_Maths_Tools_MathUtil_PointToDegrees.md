# MathUtil.PointToDegrees Method 
 

Calculates the angle at which the specified point is to the origin point (0 is to the right).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float PointToDegrees(
	Point pt,
	Point origin
)
```

**VB**<br />
``` VB
Public Shared Function PointToDegrees ( 
	pt As Point,
	origin As Point
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim pt As Point
Dim origin As Point
Dim returnValue As Single

returnValue = MathUtil.PointToDegrees(pt, 
	origin)
```

**C++**<br />
``` C++
public:
static float PointToDegrees(
	Point pt, 
	Point origin
)
```

**F#**<br />
``` F#
static member PointToDegrees : 
        pt : Point * 
        origin : Point -> float32 

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: System.Drawing.Point<br />The point.</dd><dt>origin</dt><dd>Type: System.Drawing.Point<br />The origin point.</dd></dl>

#### Return Value
Type: Single<br />The resulting degrees.

## Remarks
Credits to: <a href="http://www.vcskicks.com/code-snippet/degree-to-xy.php" target="_blank">http://www.vcskicks.com/code-snippet/degree-to-xy.php</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />