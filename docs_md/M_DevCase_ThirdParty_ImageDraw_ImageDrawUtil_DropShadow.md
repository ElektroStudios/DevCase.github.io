# ImageDrawUtil.DropShadow Method 
 

Adds drop shadows to an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DropShadow(
	ref ImageElement refImageElement,
	int opacity,
	Color shadowColor,
	int shadowAngle,
	int shadowDistance,
	int shadowSoftness
)
```

**VB**<br />
``` VB
Public Shared Sub DropShadow ( 
	ByRef refImageElement As ImageElement,
	opacity As Integer,
	shadowColor As Color,
	shadowAngle As Integer,
	shadowDistance As Integer,
	shadowSoftness As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim opacity As Integer
Dim shadowColor As Color
Dim shadowAngle As Integer
Dim shadowDistance As Integer
Dim shadowSoftness As Integer

ImageDrawUtil.DropShadow(refImageElement, 
	opacity, shadowColor, shadowAngle, 
	shadowDistance, shadowSoftness)
```

**C++**<br />
``` C++
public:
static void DropShadow(
	ImageElement^% refImageElement, 
	int opacity, 
	Color shadowColor, 
	int shadowAngle, 
	int shadowDistance, 
	int shadowSoftness
)
```

**F#**<br />
``` F#
static member DropShadow : 
        refImageElement : ImageElement byref * 
        opacity : int * 
        shadowColor : Color * 
        shadowAngle : int * 
        shadowDistance : int * 
        shadowSoftness : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>opacity</dt><dd>Type: System.Int32<br />\[Missing <param name="opacity"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DropShadow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Color,System.Int32,System.Int32,System.Int32)"\]</dd><dt>shadowColor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="shadowColor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DropShadow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Color,System.Int32,System.Int32,System.Int32)"\]</dd><dt>shadowAngle</dt><dd>Type: System.Int32<br />\[Missing <param name="shadowAngle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DropShadow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Color,System.Int32,System.Int32,System.Int32)"\]</dd><dt>shadowDistance</dt><dd>Type: System.Int32<br />\[Missing <param name="shadowDistance"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DropShadow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Color,System.Int32,System.Int32,System.Int32)"\]</dd><dt>shadowSoftness</dt><dd>Type: System.Int32<br />\[Missing <param name="shadowSoftness"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DropShadow(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Drawing.Color,System.Int32,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />