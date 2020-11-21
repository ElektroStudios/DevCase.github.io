# ImageDrawUtil.Stretch Method 
 

Stretches an image to fit a given size.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Stretch(
	ref ImageElement refImageElement,
	int width,
	int height
)
```

**VB**<br />
``` VB
Public Shared Sub Stretch ( 
	ByRef refImageElement As ImageElement,
	width As Integer,
	height As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim width As Integer
Dim height As Integer

ImageDrawUtil.Stretch(refImageElement, width, 
	height)
```

**C++**<br />
``` C++
public:
static void Stretch(
	ImageElement^% refImageElement, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
static member Stretch : 
        refImageElement : ImageElement byref * 
        width : int * 
        height : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>width</dt><dd>Type: System.Int32<br />\[Missing <param name="width"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Stretch(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd><dt>height</dt><dd>Type: System.Int32<br />\[Missing <param name="height"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Stretch(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />