# ColorUtil.GetPixelPen Method (Int32, Int32)
 

Gets the color of a pixel at the specified coordinates and returns a Pen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Pen GetPixelPen(
	int x,
	int y
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelPen ( 
	x As Integer,
	y As Integer
) As Pen
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer
Dim returnValue As Pen

returnValue = ColorUtil.GetPixelPen(x, 
	y)
```

**C++**<br />
``` C++
public:
static Pen^ GetPixelPen(
	int x, 
	int y
)
```

**F#**<br />
``` F#
static member GetPixelPen : 
        x : int * 
        y : int -> Pen 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The `x` coordinate.</dd><dt>y</dt><dd>Type: System.Int32<br />The `y` coordinate.</dd></dl>

#### Return Value
Type: Pen<br />The Pen.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelPen">GetPixelPen Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />