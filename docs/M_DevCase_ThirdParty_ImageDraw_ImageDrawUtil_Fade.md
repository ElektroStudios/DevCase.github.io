# ImageDrawUtil.Fade Method 
 

Performs fading. 

 Fading action/effect gradually fades a given area/region of the target Element into the background.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Fade(
	ref ImageElement refImageElement,
	FadeShape fadeShape,
	FillType fillType,
	GradientShape gradientShape,
	FadeLocation location = FadeLocation.Center,
	int locationX = 1,
	int locationY = 1,
	FadeSizing sizing = FadeSizing.Fit,
	int sizingHeight = 1,
	int sizingWidth = 1
)
```

**VB**<br />
``` VB
Public Shared Sub Fade ( 
	ByRef refImageElement As ImageElement,
	fadeShape As FadeShape,
	fillType As FillType,
	gradientShape As GradientShape,
	Optional location As FadeLocation = FadeLocation.Center,
	Optional locationX As Integer = 1,
	Optional locationY As Integer = 1,
	Optional sizing As FadeSizing = FadeSizing.Fit,
	Optional sizingHeight As Integer = 1,
	Optional sizingWidth As Integer = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim fadeShape As FadeShape
Dim fillType As FillType
Dim gradientShape As GradientShape
Dim location As FadeLocation
Dim locationX As Integer
Dim locationY As Integer
Dim sizing As FadeSizing
Dim sizingHeight As Integer
Dim sizingWidth As Integer

ImageDrawUtil.Fade(refImageElement, fadeShape, 
	fillType, gradientShape, location, 
	locationX, locationY, sizing, sizingHeight, 
	sizingWidth)
```

**C++**<br />
``` C++
public:
static void Fade(
	ImageElement^% refImageElement, 
	FadeShape fadeShape, 
	FillType fillType, 
	GradientShape gradientShape, 
	FadeLocation location = FadeLocation::Center, 
	int locationX = 1, 
	int locationY = 1, 
	FadeSizing sizing = FadeSizing::Fit, 
	int sizingHeight = 1, 
	int sizingWidth = 1
)
```

**F#**<br />
``` F#
static member Fade : 
        refImageElement : ImageElement byref * 
        fadeShape : FadeShape * 
        fillType : FillType * 
        gradientShape : GradientShape * 
        ?location : FadeLocation * 
        ?locationX : int * 
        ?locationY : int * 
        ?sizing : FadeSizing * 
        ?sizingHeight : int * 
        ?sizingWidth : int 
(* Defaults:
        let _location = defaultArg location FadeLocation.Center
        let _locationX = defaultArg locationX 1
        let _locationY = defaultArg locationY 1
        let _sizing = defaultArg sizing FadeSizing.Fit
        let _sizingHeight = defaultArg sizingHeight 1
        let _sizingWidth = defaultArg sizingWidth 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>fadeShape</dt><dd>Type: FadeShape<br />\[Missing <param name="fadeShape"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>fillType</dt><dd>Type: FillType<br />\[Missing <param name="fillType"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>gradientShape</dt><dd>Type: GradientShape<br />\[Missing <param name="gradientShape"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>location (Optional)</dt><dd>Type: FadeLocation<br />\[Missing <param name="location"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>locationX (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="locationX"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>locationY (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="locationY"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>sizing (Optional)</dt><dd>Type: FadeSizing<br />\[Missing <param name="sizing"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>sizingHeight (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="sizingHeight"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd><dt>sizingWidth (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="sizingWidth"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Fade(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FadeShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,Neodynamic.SDK.ImageDraw.FadeLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FadeSizing,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />