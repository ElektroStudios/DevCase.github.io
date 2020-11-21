# ColorUtil.GetPixelColor Method (Point)
 

Gets the color of a pixel at the specified coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color GetPixelColor(
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelColor ( 
	location As Point
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim location As Point
Dim returnValue As Color

returnValue = ColorUtil.GetPixelColor(location)
```

**C++**<br />
``` C++
public:
static Color GetPixelColor(
	Point location
)
```

**F#**<br />
``` F#
static member GetPixelColor : 
        location : Point -> Color 

```


#### Parameters
&nbsp;<dl><dt>location</dt><dd>Type: System.Drawing.Point<br />The (`x`,y`y`) coordinates.</dd></dl>

#### Return Value
Type: Color<br />The color of the pixel.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelColor">GetPixelColor Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />