# ImageDrawUtil.Crop Method 
 

Crops a rectangular section from an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Crop(
	ref ImageElement refImageElement,
	int x,
	int y,
	int width,
	int height
)
```

**VB**<br />
``` VB
Public Shared Sub Crop ( 
	ByRef refImageElement As ImageElement,
	x As Integer,
	y As Integer,
	width As Integer,
	height As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim height As Integer

ImageDrawUtil.Crop(refImageElement, x, y, width, 
	height)
```

**C++**<br />
``` C++
public:
static void Crop(
	ImageElement^% refImageElement, 
	int x, 
	int y, 
	int width, 
	int height
)
```

**F#**<br />
``` F#
static member Crop : 
        refImageElement : ImageElement byref * 
        x : int * 
        y : int * 
        width : int * 
        height : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>x</dt><dd>Type: System.Int32<br />\[Missing <param name="x"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Crop(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>y</dt><dd>Type: System.Int32<br />\[Missing <param name="y"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Crop(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>width</dt><dd>Type: System.Int32<br />\[Missing <param name="width"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Crop(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>height</dt><dd>Type: System.Int32<br />\[Missing <param name="height"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Crop(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />