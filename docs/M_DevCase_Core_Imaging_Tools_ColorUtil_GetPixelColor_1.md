# ColorUtil.GetPixelColor Method (Int32, Int32)
 

Gets the color of a pixel at the specified coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color GetPixelColor(
	int x,
	int y
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelColor ( 
	x As Integer,
	y As Integer
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer
Dim returnValue As Color

returnValue = ColorUtil.GetPixelColor(x, 
	y)
```

**C++**<br />
``` C++
public:
static Color GetPixelColor(
	int x, 
	int y
)
```

**F#**<br />
``` F#
static member GetPixelColor : 
        x : int * 
        y : int -> Color 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The `x` coordinate.</dd><dt>y</dt><dd>Type: System.Int32<br />The `y` coordinate.</dd></dl>

#### Return Value
Type: Color<br />The color of the pixel.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelColor">GetPixelColor Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />