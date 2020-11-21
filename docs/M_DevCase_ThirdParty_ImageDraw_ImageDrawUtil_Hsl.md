# ImageDrawUtil.Hsl Method 
 

Adjusts the Hue channel, saturation, and lightness levels of an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Hsl(
	ref ImageElement refImageElement,
	int hueAngle,
	int lightnessLevel,
	int saturationLevel
)
```

**VB**<br />
``` VB
Public Shared Sub Hsl ( 
	ByRef refImageElement As ImageElement,
	hueAngle As Integer,
	lightnessLevel As Integer,
	saturationLevel As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim hueAngle As Integer
Dim lightnessLevel As Integer
Dim saturationLevel As Integer

ImageDrawUtil.Hsl(refImageElement, hueAngle, 
	lightnessLevel, saturationLevel)
```

**C++**<br />
``` C++
public:
static void Hsl(
	ImageElement^% refImageElement, 
	int hueAngle, 
	int lightnessLevel, 
	int saturationLevel
)
```

**F#**<br />
``` F#
static member Hsl : 
        refImageElement : ImageElement byref * 
        hueAngle : int * 
        lightnessLevel : int * 
        saturationLevel : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>hueAngle</dt><dd>Type: System.Int32<br />\[Missing <param name="hueAngle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Hsl(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32)"\]</dd><dt>lightnessLevel</dt><dd>Type: System.Int32<br />\[Missing <param name="lightnessLevel"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Hsl(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32)"\]</dd><dt>saturationLevel</dt><dd>Type: System.Int32<br />\[Missing <param name="saturationLevel"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Hsl(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />