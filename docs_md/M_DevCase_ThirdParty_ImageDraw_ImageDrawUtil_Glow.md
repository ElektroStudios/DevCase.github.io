# ImageDrawUtil.Glow Method 
 

Adds glow effect to an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Glow(
	ref ImageElement refImageElement,
	Color glowColor,
	int opacity,
	int softness
)
```

**VB**<br />
``` VB
Public Shared Sub Glow ( 
	ByRef refImageElement As ImageElement,
	glowColor As Color,
	opacity As Integer,
	softness As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim glowColor As Color
Dim opacity As Integer
Dim softness As Integer

ImageDrawUtil.Glow(refImageElement, glowColor, 
	opacity, softness)
```

**C++**<br />
``` C++
public:
static void Glow(
	ImageElement^% refImageElement, 
	Color glowColor, 
	int opacity, 
	int softness
)
```

**F#**<br />
``` F#
static member Glow : 
        refImageElement : ImageElement byref * 
        glowColor : Color * 
        opacity : int * 
        softness : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>glowColor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="glowColor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Glow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Int32,System.Int32)"\]</dd><dt>opacity</dt><dd>Type: System.Int32<br />\[Missing <param name="opacity"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Glow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Int32,System.Int32)"\]</dd><dt>softness</dt><dd>Type: System.Int32<br />\[Missing <param name="softness"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Glow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />