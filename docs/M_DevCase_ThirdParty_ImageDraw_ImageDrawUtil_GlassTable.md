# ImageDrawUtil.GlassTable Method 
 

Creates a glass table effect on an image. The glass table effect adds a reflection of an image just below it.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void GlassTable(
	ref ImageElement refImageElement,
	int reflectionOpacity,
	int reflectionPercentage,
	ReflectionLocation reflectionLocation = ReflectionLocation.Auto,
	int reflectionLocationX = 1,
	int reflectionLocationY = 1
)
```

**VB**<br />
``` VB
Public Shared Sub GlassTable ( 
	ByRef refImageElement As ImageElement,
	reflectionOpacity As Integer,
	reflectionPercentage As Integer,
	Optional reflectionLocation As ReflectionLocation = ReflectionLocation.Auto,
	Optional reflectionLocationX As Integer = 1,
	Optional reflectionLocationY As Integer = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim reflectionOpacity As Integer
Dim reflectionPercentage As Integer
Dim reflectionLocation As ReflectionLocation
Dim reflectionLocationX As Integer
Dim reflectionLocationY As Integer

ImageDrawUtil.GlassTable(refImageElement, 
	reflectionOpacity, reflectionPercentage, 
	reflectionLocation, reflectionLocationX, 
	reflectionLocationY)
```

**C++**<br />
``` C++
public:
static void GlassTable(
	ImageElement^% refImageElement, 
	int reflectionOpacity, 
	int reflectionPercentage, 
	ReflectionLocation reflectionLocation = ReflectionLocation::Auto, 
	int reflectionLocationX = 1, 
	int reflectionLocationY = 1
)
```

**F#**<br />
``` F#
static member GlassTable : 
        refImageElement : ImageElement byref * 
        reflectionOpacity : int * 
        reflectionPercentage : int * 
        ?reflectionLocation : ReflectionLocation * 
        ?reflectionLocationX : int * 
        ?reflectionLocationY : int 
(* Defaults:
        let _reflectionLocation = defaultArg reflectionLocation ReflectionLocation.Auto
        let _reflectionLocationX = defaultArg reflectionLocationX 1
        let _reflectionLocationY = defaultArg reflectionLocationY 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>reflectionOpacity</dt><dd>Type: System.Int32<br />\[Missing <param name="reflectionOpacity"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GlassTable(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.ReflectionLocation,System.Int32,System.Int32)"\]</dd><dt>reflectionPercentage</dt><dd>Type: System.Int32<br />\[Missing <param name="reflectionPercentage"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GlassTable(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.ReflectionLocation,System.Int32,System.Int32)"\]</dd><dt>reflectionLocation (Optional)</dt><dd>Type: ReflectionLocation<br />\[Missing <param name="reflectionLocation"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GlassTable(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.ReflectionLocation,System.Int32,System.Int32)"\]</dd><dt>reflectionLocationX (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="reflectionLocationX"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GlassTable(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.ReflectionLocation,System.Int32,System.Int32)"\]</dd><dt>reflectionLocationY (Optional)</dt><dd>Type: System.Int32<br />\[Missing <param name="reflectionLocationY"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.GlassTable(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.ReflectionLocation,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />