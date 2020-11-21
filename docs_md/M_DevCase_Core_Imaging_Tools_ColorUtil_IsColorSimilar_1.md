# ColorUtil.IsColorSimilar Method (Color, Color, Byte, Byte, Byte)
 

Determines whether two colors are similar. 

 It compares the RGB channel differences to match inside the range of the specified tolerance threshold values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsColorSimilar(
	Color color1,
	Color color2,
	byte thresholdR,
	byte thresholdG,
	byte thresholdB
)
```

**VB**<br />
``` VB
Public Shared Function IsColorSimilar ( 
	color1 As Color,
	color2 As Color,
	thresholdR As Byte,
	thresholdG As Byte,
	thresholdB As Byte
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim color1 As Color
Dim color2 As Color
Dim thresholdR As Byte
Dim thresholdG As Byte
Dim thresholdB As Byte
Dim returnValue As Boolean

returnValue = ColorUtil.IsColorSimilar(color1, 
	color2, thresholdR, thresholdG, thresholdB)
```

**C++**<br />
``` C++
public:
static bool IsColorSimilar(
	Color color1, 
	Color color2, 
	unsigned char thresholdR, 
	unsigned char thresholdG, 
	unsigned char thresholdB
)
```

**F#**<br />
``` F#
static member IsColorSimilar : 
        color1 : Color * 
        color2 : Color * 
        thresholdR : byte * 
        thresholdG : byte * 
        thresholdB : byte -> bool 

```


#### Parameters
&nbsp;<dl><dt>color1</dt><dd>Type: System.Drawing.Color<br />The first color to compare.</dd><dt>color2</dt><dd>Type: System.Drawing.Color<br />The second color to compare.</dd><dt>thresholdR</dt><dd>Type: System.Byte<br />The tolerance threshold of the Red color channel. From 0 to 255.</dd><dt>thresholdG</dt><dd>Type: System.Byte<br />The tolerance threshold of the Green color channel. From 0 to 255.</dd><dt>thresholdB</dt><dd>Type: System.Byte<br />The tolerance threshold of the Blue color channel. From 0 to 255.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the colors are similar, this means the RGB differences matches inside the range of the specified tolerance threshold value, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim areSimilar As Boolean = IsColorSimilar(Color.FromArgb(0, 0, 0), Color.FromArgb(0, 0, 1),
                                           thresholdR:=0, thresholdG:=0, thresholdB:=1)
' Result: True
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_IsColorSimilar">IsColorSimilar Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />