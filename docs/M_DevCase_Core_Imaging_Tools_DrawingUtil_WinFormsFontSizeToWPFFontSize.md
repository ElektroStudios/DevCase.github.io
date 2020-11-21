# DrawingUtil.WinFormsFontSizeToWPFFontSize Method (Font)
 

Converts a WinForms font size to WPF font size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float WinFormsFontSizeToWPFFontSize(
	Font font
)
```

**VB**<br />
``` VB
Public Shared Function WinFormsFontSizeToWPFFontSize ( 
	font As Font
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim font As Font
Dim returnValue As Single

returnValue = DrawingUtil.WinFormsFontSizeToWPFFontSize(font)
```

**C++**<br />
``` C++
public:
static float WinFormsFontSizeToWPFFontSize(
	Font^ font
)
```

**F#**<br />
``` F#
static member WinFormsFontSizeToWPFFontSize : 
        font : Font -> float32 

```


#### Parameters
&nbsp;<dl><dt>font</dt><dd>Type: System.Drawing.Font<br />The WinForms font.</dd></dl>

#### Return Value
Type: Single<br />The resulting WPF font size.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_WinFormsFontSizeToWPFFontSize">WinFormsFontSizeToWPFFontSize Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />