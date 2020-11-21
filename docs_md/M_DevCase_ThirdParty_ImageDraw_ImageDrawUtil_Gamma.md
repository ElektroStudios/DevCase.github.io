# ImageDrawUtil.Gamma Method 
 

Adjusts the gamma correction value of an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Gamma(
	ref ImageElement refImageElement,
	int gammaCorrectionValue
)
```

**VB**<br />
``` VB
Public Shared Sub Gamma ( 
	ByRef refImageElement As ImageElement,
	gammaCorrectionValue As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim gammaCorrectionValue As Integer

ImageDrawUtil.Gamma(refImageElement, gammaCorrectionValue)
```

**C++**<br />
``` C++
public:
static void Gamma(
	ImageElement^% refImageElement, 
	int gammaCorrectionValue
)
```

**F#**<br />
``` F#
static member Gamma : 
        refImageElement : ImageElement byref * 
        gammaCorrectionValue : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>gammaCorrectionValue</dt><dd>Type: System.Int32<br />\[Missing <param name="gammaCorrectionValue"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Gamma(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />