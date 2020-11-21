# ColorUtil.GetPixelBrush Method (Point)
 

Gets the color of a pixel at the specified coordinates and returns a Brush.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SolidBrush GetPixelBrush(
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelBrush ( 
	location As Point
) As SolidBrush
```

**VB Usage**<br />
``` VB Usage
Dim location As Point
Dim returnValue As SolidBrush

returnValue = ColorUtil.GetPixelBrush(location)
```

**C++**<br />
``` C++
public:
static SolidBrush^ GetPixelBrush(
	Point location
)
```

**F#**<br />
``` F#
static member GetPixelBrush : 
        location : Point -> SolidBrush 

```


#### Parameters
&nbsp;<dl><dt>location</dt><dd>Type: System.Drawing.Point<br />The (`x`,y`y`) coordinates.</dd></dl>

#### Return Value
Type: SolidBrush<br />The Brush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelBrush">GetPixelBrush Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />