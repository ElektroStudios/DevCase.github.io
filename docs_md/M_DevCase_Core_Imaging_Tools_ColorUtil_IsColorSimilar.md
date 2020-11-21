# ColorUtil.IsColorSimilar Method (Color, Color, Byte)
 

Determines whether two colors are similar. 

 It compares the RGB channel difference to match inside the range of the specified tolerance threshold value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsColorSimilar(
	Color color1,
	Color color2,
	byte threshold
)
```

**VB**<br />
``` VB
Public Shared Function IsColorSimilar ( 
	color1 As Color,
	color2 As Color,
	threshold As Byte
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim color1 As Color
Dim color2 As Color
Dim threshold As Byte
Dim returnValue As Boolean

returnValue = ColorUtil.IsColorSimilar(color1, 
	color2, threshold)
```

**C++**<br />
``` C++
public:
static bool IsColorSimilar(
	Color color1, 
	Color color2, 
	unsigned char threshold
)
```

**F#**<br />
``` F#
static member IsColorSimilar : 
        color1 : Color * 
        color2 : Color * 
        threshold : byte -> bool 

```


#### Parameters
&nbsp;<dl><dt>color1</dt><dd>Type: System.Drawing.Color<br />The first color to compare.</dd><dt>color2</dt><dd>Type: System.Drawing.Color<br />The second color to compare.</dd><dt>threshold</dt><dd>Type: System.Byte<br />The global tolerance threshold of the RGB color channels. From 0 to 255.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the colors are similar, this means the RGB differences matches inside the range of the specified tolerance threshold value, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result1 As Boolean = IsColorSimilar(Color.FromArgb(0, 0, 0), Color.FromArgb(0, 0, 1), threshold:=1)
' Result: True
'  Logic: Blue channel difference = 1, which is equal than the specified tolerance threshold value.

Dim result2 As Boolean = IsColorSimilar(Color.FromArgb(0, 0, 0), Color.FromArgb(0, 1, 1), threshold:=1)
' Result: False
'  Logic: Red channel + Blue channel differences = 2, which is a bigger value than the specified tolerance threshold value.
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_IsColorSimilar">IsColorSimilar Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />