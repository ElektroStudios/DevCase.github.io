# ImageDrawUtil.Scale Method 
 

Enlarges or reduces the size of an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Scale(
	ref ImageElement refImageElement,
	int widthPercentage,
	int heightPercentage,
	InterpolationMode interpolationMode
)
```

**VB**<br />
``` VB
Public Shared Sub Scale ( 
	ByRef refImageElement As ImageElement,
	widthPercentage As Integer,
	heightPercentage As Integer,
	interpolationMode As InterpolationMode
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim widthPercentage As Integer
Dim heightPercentage As Integer
Dim interpolationMode As InterpolationModeImageDrawUtil.Scale(refImageElement, widthPercentage, 
	heightPercentage, interpolationMode)
```

**C++**<br />
``` C++
public:
static void Scale(
	ImageElement^% refImageElement, 
	int widthPercentage, 
	int heightPercentage, 
	InterpolationMode interpolationMode
)
```

**F#**<br />
``` F#
static member Scale : 
        refImageElement : ImageElement byref * 
        widthPercentage : int * 
        heightPercentage : int * 
        interpolationMode : InterpolationMode -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>widthPercentage</dt><dd>Type: System.Int32<br />\[Missing <param name="widthPercentage"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Scale(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>heightPercentage</dt><dd>Type: System.Int32<br />\[Missing <param name="heightPercentage"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Scale(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>interpolationMode</dt><dd>Type: System.Drawing.Drawing2D.InterpolationMode<br />\[Missing <param name="interpolationMode"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Scale(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Drawing.Drawing2D.InterpolationMode)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />