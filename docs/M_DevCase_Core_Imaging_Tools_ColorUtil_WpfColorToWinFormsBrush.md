# ColorUtil.WpfColorToWinFormsBrush Method 
 

Converts a WPF brush (Color) to WinForms brush (Brush).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Brush WpfColorToWinFormsBrush(
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function WpfColorToWinFormsBrush ( 
	color As Color
) As Brush
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim returnValue As Brush

returnValue = ColorUtil.WpfColorToWinFormsBrush(color)
```

**C++**<br />
``` C++
public:
static Brush^ WpfColorToWinFormsBrush(
	Color color
)
```

**F#**<br />
``` F#
static member WpfColorToWinFormsBrush : 
        color : Color -> Brush 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Windows.Media.Color<br />The WPF color.</dd></dl>

#### Return Value
Type: Brush<br />The resulting WinForms brush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />