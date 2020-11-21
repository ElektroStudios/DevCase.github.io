# ColorUtil.ConsoleColorToWinFormsColor Method 
 

Converts a ConsoleColor to its equivalent Color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color ConsoleColorToWinFormsColor(
	ConsoleColor color
)
```

**VB**<br />
``` VB
Public Shared Function ConsoleColorToWinFormsColor ( 
	color As ConsoleColor
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim color As ConsoleColor
Dim returnValue As Color

returnValue = ColorUtil.ConsoleColorToWinFormsColor(color)
```

**C++**<br />
``` C++
public:
static Color ConsoleColorToWinFormsColor(
	ConsoleColor color
)
```

**F#**<br />
``` F#
static member ConsoleColorToWinFormsColor : 
        color : ConsoleColor -> Color 

```


#### Parameters
&nbsp;<dl><dt>color</dt><dd>Type: System.ConsoleColor<br />The source ConsoleColor.</dd></dl>

#### Return Value
Type: Color<br />The resulting Color.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />