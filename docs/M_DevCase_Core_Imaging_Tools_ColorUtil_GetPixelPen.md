# ColorUtil.GetPixelPen Method (Point)
 

Gets the color of a pixel at the specified coordinates and returns a Pen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Pen GetPixelPen(
	Point location
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelPen ( 
	location As Point
) As Pen
```

**VB Usage**<br />
``` VB Usage
Dim location As Point
Dim returnValue As Pen

returnValue = ColorUtil.GetPixelPen(location)
```

**C++**<br />
``` C++
public:
static Pen^ GetPixelPen(
	Point location
)
```

**F#**<br />
``` F#
static member GetPixelPen : 
        location : Point -> Pen 

```


#### Parameters
&nbsp;<dl><dt>location</dt><dd>Type: System.Drawing.Point<br />The (`x`,y`y`) coordinates.</dd></dl>

#### Return Value
Type: Pen<br />The Pen.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelPen">GetPixelPen Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />