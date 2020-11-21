# ColorUtil.WinFormsColorToWpfBrush Method 
 

Converts a WinForms color (Color) to WPF brush (Brush).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Brush WinFormsColorToWpfBrush(
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function WinFormsColorToWpfBrush ( 
	color As Color
) As Brush
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim returnValue As Brush

returnValue = ColorUtil.WinFormsColorToWpfBrush(color)
```

**C++**<br />
``` C++
public:
static Brush^ WinFormsColorToWpfBrush(
	Color color
)
```

**F#**<br />
``` F#
static member WinFormsColorToWpfBrush : 
        color : Color -> Brush 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />The WinForms color.</dd></dl>

#### Return Value
Type: Brush<br />The resulting WPF brush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />