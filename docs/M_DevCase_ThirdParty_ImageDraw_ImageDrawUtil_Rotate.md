# ImageDrawUtil.Rotate Method 
 

Rotates an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Rotate(
	ref ImageElement refImageElement,
	int angle,
	InterpolationMode interpolationMode
)
```

**VB**<br />
``` VB
Public Shared Sub Rotate ( 
	ByRef refImageElement As ImageElement,
	angle As Integer,
	interpolationMode As InterpolationMode
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim angle As Integer
Dim interpolationMode As InterpolationModeImageDrawUtil.Rotate(refImageElement, angle, 
	interpolationMode)
```

**C++**<br />
``` C++
public:
static void Rotate(
	ImageElement^% refImageElement, 
	int angle, 
	InterpolationMode interpolationMode
)
```

**F#**<br />
``` F#
static member Rotate : 
        refImageElement : ImageElement byref * 
        angle : int * 
        interpolationMode : InterpolationMode -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>angle</dt><dd>Type: System.Int32<br />\[Missing <param name="angle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Rotate(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>interpolationMode</dt><dd>Type: System.Drawing.Drawing2D.InterpolationMode<br />\[Missing <param name="interpolationMode"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Rotate(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Drawing2D.InterpolationMode)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />