# ColorUtil.WinFormsBrushToWpfBrush Method 
 

Converts a WinForms brush (Brush) to WPF brush (Brush).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Brush WinFormsBrushToWpfBrush(
	Brush brush
)
```

**VB**<br />
``` VB
Public Shared Function WinFormsBrushToWpfBrush ( 
	brush As Brush
) As Brush
```

**VB Usage**<br />
``` VB Usage
Dim brush As Brush
Dim returnValue As Brush

returnValue = ColorUtil.WinFormsBrushToWpfBrush(brush)
```

**C++**<br />
``` C++
public:
static Brush^ WinFormsBrushToWpfBrush(
	Brush^ brush
)
```

**F#**<br />
``` F#
static member WinFormsBrushToWpfBrush : 
        brush : Brush -> Brush 

```


#### Parameters
&nbsp;<dl><dt>brush</dt><dd>Type: System.Drawing.Brush<br />The WinForms brush.</dd></dl>

#### Return Value
Type: Brush<br />The resulting WPF brush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />