# ImageDrawUtil.ColorSubstitution Method 
 

Replaces one color (old color) with another (new color) on an element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ColorSubstitution(
	ref ImageElement refImageElement,
	Color oldColor,
	Color newcolor,
	byte colorTolerance
)
```

**VB**<br />
``` VB
Public Shared Sub ColorSubstitution ( 
	ByRef refImageElement As ImageElement,
	oldColor As Color,
	newcolor As Color,
	colorTolerance As Byte
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim oldColor As Color
Dim newcolor As Color
Dim colorTolerance As ByteImageDrawUtil.ColorSubstitution(refImageElement, 
	oldColor, newcolor, colorTolerance)
```

**C++**<br />
``` C++
public:
static void ColorSubstitution(
	ImageElement^% refImageElement, 
	Color oldColor, 
	Color newcolor, 
	unsigned char colorTolerance
)
```

**F#**<br />
``` F#
static member ColorSubstitution : 
        refImageElement : ImageElement byref * 
        oldColor : Color * 
        newcolor : Color * 
        colorTolerance : byte -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>oldColor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="oldColor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ColorSubstitution(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Drawing.Color,System.Byte)"\]</dd><dt>newcolor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="newcolor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ColorSubstitution(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Drawing.Color,System.Byte)"\]</dd><dt>colorTolerance</dt><dd>Type: System.Byte<br />\[Missing <param name="colorTolerance"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.ColorSubstitution(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Drawing.Color,System.Byte)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />