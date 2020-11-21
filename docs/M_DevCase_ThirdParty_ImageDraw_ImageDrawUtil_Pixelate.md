# ImageDrawUtil.Pixelate Method 
 

Pixelates an element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Pixelate(
	ref ImageElement refImageElement,
	int pixelSize,
	int fadePercent
)
```

**VB**<br />
``` VB
Public Shared Sub Pixelate ( 
	ByRef refImageElement As ImageElement,
	pixelSize As Integer,
	fadePercent As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim pixelSize As Integer
Dim fadePercent As Integer

ImageDrawUtil.Pixelate(refImageElement, pixelSize, 
	fadePercent)
```

**C++**<br />
``` C++
public:
static void Pixelate(
	ImageElement^% refImageElement, 
	int pixelSize, 
	int fadePercent
)
```

**F#**<br />
``` F#
static member Pixelate : 
        refImageElement : ImageElement byref * 
        pixelSize : int * 
        fadePercent : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>pixelSize</dt><dd>Type: System.Int32<br />\[Missing <param name="pixelSize"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Pixelate(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd><dt>fadePercent</dt><dd>Type: System.Int32<br />\[Missing <param name="fadePercent"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Pixelate(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />