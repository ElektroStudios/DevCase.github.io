# ImageDrawUtil.FocalGrayscale Method 
 

Creates grayscale element with a colored focal point represented by a shape.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void FocalGrayscale(
	ref ImageElement refImageElement,
	FocalShape focalShape,
	FillType fillType,
	GradientShape gradientShape,
	Color gradientColor1,
	Color gradientColor2,
	FocalLocation location = FocalLocation.Center,
	int locationX = 1,
	int locationY = 1,
	FocalSizing sizing = FocalSizing.Fit,
	int sizingHeight = 1,
	int sizingWidth = 1
)
```

**VB**<br />
``` VB
Public Shared Sub FocalGrayscale ( 
	ByRef refImageElement As ImageElement,
	focalShape As FocalShape,
	fillType As FillType,
	gradientShape As GradientShape,
	gradientColor1 As Color,
	gradientColor2 As Color,
	Optional location As FocalLocation = FocalLocation.Center,
	Optional locationX As Integer = 1,
	Optional locationY As Integer = 1,
	Optional sizing As FocalSizing = FocalSizing.Fit,
	Optional sizingHeight As Integer = 1,
	Optional sizingWidth As Integer = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim focalShape As FocalShape
Dim fillType As FillType
Dim gradientShape As GradientShape
Dim gradientColor1 As Color
Dim gradientColor2 As Color
Dim location As FocalLocation
Dim locationX As Integer
Dim locationY As Integer
Dim sizing As FocalSizing
Dim sizingHeight As Integer
Dim sizingWidth As Integer

ImageDrawUtil.FocalGrayscale(refImageElement, 
	focalShape, fillType, gradientShape, 
	gradientColor1, gradientColor2, 
	location, locationX, locationY, sizing, 
	sizingHeight, sizingWidth)
```

**C++**<br />
``` C++
public:
static void FocalGrayscale(
	ImageElement^% refImageElement, 
	FocalShape focalShape, 
	FillType fillType, 
	GradientShape gradientShape, 
	Color gradientColor1, 
	Color gradientColor2, 
	FocalLocation location = FocalLocation::Center, 
	int locationX = 1, 
	int locationY = 1, 
	FocalSizing sizing = FocalSizing::Fit, 
	int sizingHeight = 1, 
	int sizingWidth = 1
)
```

**F#**<br />
``` F#
static member FocalGrayscale : 
        refImageElement : ImageElement byref * 
        focalShape : FocalShape * 
        fillType : FillType * 
        gradientShape : GradientShape * 
        gradientColor1 : Color * 
        gradientColor2 : Color * 
        ?location : FocalLocation * 
        ?locationX : int * 
        ?locationY : int * 
        ?sizing : FocalSizing * 
        ?sizingHeight : int * 
        ?sizingWidth : int 
(* Defaults:
        let _location = defaultArg location FocalLocation.Center
        let _locationX = defaultArg locationX 1
        let _locationY = defaultArg locationY 1
        let _sizing = defaultArg sizing FocalSizing.Fit
        let _sizingHeight = defaultArg sizingHeight 1
        let _sizingWidth = defaultArg sizingWidth 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>focalShape</dt><dd>Type: FocalShape<br />\[Missing <param name="focalShape"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>fillType</dt><dd>Type: FillType<br />\[Missing <param name="fillType"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>gradientShape</dt><dd>Type: GradientShape<br />\[Missing <param name="gradientShape"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>gradientColor1</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="gradientColor1"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>gradientColor2</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="gradientColor2"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>location (Optional)</dt><dd>Type: FocalLocation<br />\[Missing <param name="location"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>locationX (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="locationX"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>locationY (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="locationY"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>sizing (Optional)</dt><dd>Type: FocalSizing<br />\[Missing <param name="sizing"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>sizingHeight (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="sizingHeight"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd><dt>sizingWidth (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="sizingWidth"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.FocalGrayscale(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.FocalShape,Neodynamic.SDK.ImageDraw.FillType,Neodynamic.SDK.ImageDraw.GradientShape,System.Drawing.Color,System.Drawing.Color,Neodynamic.SDK.ImageDraw.FocalLocation,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.FocalSizing,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />