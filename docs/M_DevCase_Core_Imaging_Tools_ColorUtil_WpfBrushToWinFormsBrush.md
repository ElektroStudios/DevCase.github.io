# ColorUtil.WpfBrushToWinFormsBrush Method 
 

Converts a WPF brush (Brush) to WinForms brush (Brush).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Brush WpfBrushToWinFormsBrush(
	Brush brush
)
```

**VB**<br />
``` VB
Public Shared Function WpfBrushToWinFormsBrush ( 
	brush As Brush
) As Brush
```

**VB Usage**<br />
``` VB Usage
Dim brush As Brush
Dim returnValue As Brush

returnValue = ColorUtil.WpfBrushToWinFormsBrush(brush)
```

**C++**<br />
``` C++
public:
static Brush^ WpfBrushToWinFormsBrush(
	Brush^ brush
)
```

**F#**<br />
``` F#
static member WpfBrushToWinFormsBrush : 
        brush : Brush -> Brush 

```


#### Parameters
&nbsp;<dl><dt>brush</dt><dd>Type: System.Windows.Media.Brush<br />The WPF brush.</dd></dl>

#### Return Value
Type: Brush<br />The resulting WinForms brush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />