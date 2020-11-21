# ScreenRegionSelector Constructor (Color, Int32, Color, Double)
 

Initializes a new instance of the <a href="T_DevCase_Core_Imaging_ScreenRegionSelector">ScreenRegionSelector</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ScreenRegionSelector(
	Color borderColor,
	int borderSize,
	Color backgroundColor,
	double backgroundOpacity
)
```

**VB**<br />
``` VB
Public Sub New ( 
	borderColor As Color,
	borderSize As Integer,
	backgroundColor As Color,
	backgroundOpacity As Double
)
```

**VB Usage**<br />
``` VB Usage
Dim borderColor As Color
Dim borderSize As Integer
Dim backgroundColor As Color
Dim backgroundOpacity As Double

Dim instance As New ScreenRegionSelector(borderColor, 
	borderSize, backgroundColor, backgroundOpacity)
```

**C++**<br />
``` C++
public:
ScreenRegionSelector(
	Color borderColor, 
	int borderSize, 
	Color backgroundColor, 
	double backgroundOpacity
)
```

**F#**<br />
``` F#
new : 
        borderColor : Color * 
        borderSize : int * 
        backgroundColor : Color * 
        backgroundOpacity : float -> ScreenRegionSelector
```


#### Parameters
&nbsp;<dl><dt>borderColor</dt><dd>Type: System.Drawing.Color<br />The border color of the region selector.</dd><dt>borderSize</dt><dd>Type: System.Int32<br />The border size of the region selector.</dd><dt>backgroundColor</dt><dd>Type: System.Drawing.Color<br />The background color of the region selector.</dd><dt>backgroundOpacity</dt><dd>Type: System.Double<br />The background opacity of the region selector.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_ScreenRegionSelector">ScreenRegionSelector Class</a><br /><a href="Overload_DevCase_Core_Imaging_ScreenRegionSelector__ctor">ScreenRegionSelector Overload</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />