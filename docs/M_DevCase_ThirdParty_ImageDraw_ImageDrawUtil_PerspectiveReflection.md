# ImageDrawUtil.PerspectiveReflection Method 
 

Adds perspective reflection to an element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void PerspectiveReflection(
	ref ImageElement refImageElement,
	int angle,
	int opacity,
	int length,
	int widthPercentage,
	int offsetY
)
```

**VB**<br />
``` VB
Public Shared Sub PerspectiveReflection ( 
	ByRef refImageElement As ImageElement,
	angle As Integer,
	opacity As Integer,
	length As Integer,
	widthPercentage As Integer,
	offsetY As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim angle As Integer
Dim opacity As Integer
Dim length As Integer
Dim widthPercentage As Integer
Dim offsetY As Integer

ImageDrawUtil.PerspectiveReflection(refImageElement, 
	angle, opacity, length, widthPercentage, 
	offsetY)
```

**C++**<br />
``` C++
public:
static void PerspectiveReflection(
	ImageElement^% refImageElement, 
	int angle, 
	int opacity, 
	int length, 
	int widthPercentage, 
	int offsetY
)
```

**F#**<br />
``` F#
static member PerspectiveReflection : 
        refImageElement : ImageElement byref * 
        angle : int * 
        opacity : int * 
        length : int * 
        widthPercentage : int * 
        offsetY : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>angle</dt><dd>Type: System.Int32<br />\[Missing <param name="angle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.PerspectiveReflection(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>opacity</dt><dd>Type: System.Int32<br />\[Missing <param name="opacity"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.PerspectiveReflection(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>length</dt><dd>Type: System.Int32<br />\[Missing <param name="length"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.PerspectiveReflection(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>widthPercentage</dt><dd>Type: System.Int32<br />\[Missing <param name="widthPercentage"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.PerspectiveReflection(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>offsetY</dt><dd>Type: System.Int32<br />\[Missing <param name="offsetY"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.PerspectiveReflection(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />