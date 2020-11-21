# ImageDrawUtil.ConvertToBlackWhite Method 
 

Converts an element to black/white or monochrome.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ConvertToBlackWhite(
	ref ImageElement refImageElement,
	DitherMethod ditherMethod,
	int threshold,
	bool reverseEffect
)
```

**VB**<br />
``` VB
Public Shared Sub ConvertToBlackWhite ( 
	ByRef refImageElement As ImageElement,
	ditherMethod As DitherMethod,
	threshold As Integer,
	reverseEffect As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim ditherMethod As DitherMethod
Dim threshold As Integer
Dim reverseEffect As BooleanImageDrawUtil.ConvertToBlackWhite(refImageElement, 
	ditherMethod, threshold, reverseEffect)
```

**C++**<br />
``` C++
public:
static void ConvertToBlackWhite(
	ImageElement^% refImageElement, 
	DitherMethod ditherMethod, 
	int threshold, 
	bool reverseEffect
)
```

**F#**<br />
``` F#
static member ConvertToBlackWhite : 
        refImageElement : ImageElement byref * 
        ditherMethod : DitherMethod * 
        threshold : int * 
        reverseEffect : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>ditherMethod</dt><dd>Type: DitherMethod<br />\[Missing <param name="ditherMethod"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ConvertToBlackWhite(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.DitherMethod,System.Int32,System.Boolean)"\]</dd><dt>threshold</dt><dd>Type: System.Int32<br />\[Missing <param name="threshold"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ConvertToBlackWhite(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.DitherMethod,System.Int32,System.Boolean)"\]</dd><dt>reverseEffect</dt><dd>Type: System.Boolean<br />\[Missing <param name="reverseEffect"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ConvertToBlackWhite(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.DitherMethod,System.Int32,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />