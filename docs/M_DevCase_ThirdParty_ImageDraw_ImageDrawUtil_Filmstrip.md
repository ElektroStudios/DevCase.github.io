# ImageDrawUtil.Filmstrip Method 
 

Creates a Filmstrip representation of an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Filmstrip(
	ref ImageElement refImageElement,
	FilmstripOrientation orientation,
	int width,
	int height,
	int roundness,
	Color perforationColor,
	int perforationWidth
)
```

**VB**<br />
``` VB
Public Shared Sub Filmstrip ( 
	ByRef refImageElement As ImageElement,
	orientation As FilmstripOrientation,
	width As Integer,
	height As Integer,
	roundness As Integer,
	perforationColor As Color,
	perforationWidth As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim orientation As FilmstripOrientation
Dim width As Integer
Dim height As Integer
Dim roundness As Integer
Dim perforationColor As Color
Dim perforationWidth As Integer

ImageDrawUtil.Filmstrip(refImageElement, 
	orientation, width, height, roundness, 
	perforationColor, perforationWidth)
```

**C++**<br />
``` C++
public:
static void Filmstrip(
	ImageElement^% refImageElement, 
	FilmstripOrientation orientation, 
	int width, 
	int height, 
	int roundness, 
	Color perforationColor, 
	int perforationWidth
)
```

**F#**<br />
``` F#
static member Filmstrip : 
        refImageElement : ImageElement byref * 
        orientation : FilmstripOrientation * 
        width : int * 
        height : int * 
        roundness : int * 
        perforationColor : Color * 
        perforationWidth : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>orientation</dt><dd>Type: FilmstripOrientation<br />\[Missing <param name="orientation"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd><dt>width</dt><dd>Type: System.Int32<br />\[Missing <param name="width"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd><dt>height</dt><dd>Type: System.Int32<br />\[Missing <param name="height"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd><dt>roundness</dt><dd>Type: System.Int32<br />\[Missing <param name="roundness"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd><dt>perforationColor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="perforationColor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd><dt>perforationWidth</dt><dd>Type: System.Int32<br />\[Missing <param name="perforationWidth"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Filmstrip(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FilmstripOrientation,System.Int32,System.Int32,System.Int32,System.Drawing.Color,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />