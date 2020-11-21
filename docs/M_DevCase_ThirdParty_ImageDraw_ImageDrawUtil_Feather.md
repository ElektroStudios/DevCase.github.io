# ImageDrawUtil.Feather Method 
 

Performs feathering. Feathering blurs the edges of a given area/region on the target Element, blending it into the background.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Feather(
	ref ImageElement refImageElement,
	int featherRadius,
	FeatherShape featherShape
)
```

**VB**<br />
``` VB
Public Shared Sub Feather ( 
	ByRef refImageElement As ImageElement,
	featherRadius As Integer,
	featherShape As FeatherShape
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim featherRadius As Integer
Dim featherShape As FeatherShapeImageDrawUtil.Feather(refImageElement, featherRadius, 
	featherShape)
```

**C++**<br />
``` C++
public:
static void Feather(
	ImageElement^% refImageElement, 
	int featherRadius, 
	FeatherShape featherShape
)
```

**F#**<br />
``` F#
static member Feather : 
        refImageElement : ImageElement byref * 
        featherRadius : int * 
        featherShape : FeatherShape -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>featherRadius</dt><dd>Type: System.Int32<br />\[Missing <param name="featherRadius"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Feather(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,Neodynamic.SDK.ImageDraw.FeatherShape)"\]</dd><dt>featherShape</dt><dd>Type: FeatherShape<br />\[Missing <param name="featherShape"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Feather(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,Neodynamic.SDK.ImageDraw.FeatherShape)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />