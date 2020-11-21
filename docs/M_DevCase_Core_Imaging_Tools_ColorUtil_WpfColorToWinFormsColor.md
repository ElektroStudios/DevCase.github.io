# ColorUtil.WpfColorToWinFormsColor Method 
 

Converts a WPF color (Color) to WinForms color (Color).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color WpfColorToWinFormsColor(
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function WpfColorToWinFormsColor ( 
	color As Color
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim returnValue As Color

returnValue = ColorUtil.WpfColorToWinFormsColor(color)
```

**C++**<br />
``` C++
public:
static Color WpfColorToWinFormsColor(
	Color color
)
```

**F#**<br />
``` F#
static member WpfColorToWinFormsColor : 
        color : Color -> Color 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Windows.Media.Color<br />The WPF color.</dd></dl>

#### Return Value
Type: Color<br />The resulting WinForms color.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />