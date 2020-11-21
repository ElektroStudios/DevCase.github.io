# ImageDrawUtil.GaussianBlur Method 
 

Softens the look of an element. Gaussian Blur applies a weighted average of blur to each pixel producing a hazy effect.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void GaussianBlur(
	ref ImageElement refImageElement,
	int radius
)
```

**VB**<br />
``` VB
Public Shared Sub GaussianBlur ( 
	ByRef refImageElement As ImageElement,
	radius As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim radius As Integer

ImageDrawUtil.GaussianBlur(refImageElement, 
	radius)
```

**C++**<br />
``` C++
public:
static void GaussianBlur(
	ImageElement^% refImageElement, 
	int radius
)
```

**F#**<br />
``` F#
static member GaussianBlur : 
        refImageElement : ImageElement byref * 
        radius : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>radius</dt><dd>Type: System.Int32<br />\[Missing <param name="radius"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GaussianBlur(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />