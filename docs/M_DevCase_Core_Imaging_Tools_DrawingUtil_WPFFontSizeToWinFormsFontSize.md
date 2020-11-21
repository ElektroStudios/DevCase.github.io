# DrawingUtil.WPFFontSizeToWinFormsFontSize Method 
 

Converts a WPF font size to WinForms font size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float WPFFontSizeToWinFormsFontSize(
	float fontSize
)
```

**VB**<br />
``` VB
Public Shared Function WPFFontSizeToWinFormsFontSize ( 
	fontSize As Single
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim fontSize As Single
Dim returnValue As Single

returnValue = DrawingUtil.WPFFontSizeToWinFormsFontSize(fontSize)
```

**C++**<br />
``` C++
public:
static float WPFFontSizeToWinFormsFontSize(
	float fontSize
)
```

**F#**<br />
``` F#
static member WPFFontSizeToWinFormsFontSize : 
        fontSize : float32 -> float32 

```


#### Parameters
&nbsp;<dl><dt>fontSize</dt><dd>Type: System.Single<br />The WPF font size.</dd></dl>

#### Return Value
Type: Single<br />The resulting WinForms font size.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />