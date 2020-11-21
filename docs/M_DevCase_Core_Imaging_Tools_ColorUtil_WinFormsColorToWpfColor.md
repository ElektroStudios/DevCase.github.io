# ColorUtil.WinFormsColorToWpfColor Method 
 

Converts a WinForms color (Color) to WPF color (Color).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color WinFormsColorToWpfColor(
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function WinFormsColorToWpfColor ( 
	color As Color
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim color As Color
Dim returnValue As Color

returnValue = ColorUtil.WinFormsColorToWpfColor(color)
```

**C++**<br />
``` C++
public:
static Color WinFormsColorToWpfColor(
	Color color
)
```

**F#**<br />
``` F#
static member WinFormsColorToWpfColor : 
        color : Color -> Color 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.Drawing.Color<br />The WinForms color.</dd></dl>

#### Return Value
Type: Color<br />The resulting WPF color.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />