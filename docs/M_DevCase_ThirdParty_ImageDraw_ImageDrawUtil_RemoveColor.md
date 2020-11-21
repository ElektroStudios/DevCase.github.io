# ImageDrawUtil.RemoveColor Method 
 

Removes a color from an element and automatically resizes it.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveColor(
	ref ImageElement refImageElement,
	Color color,
	byte colorTolerance,
	ScanDirection scanDirection
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveColor ( 
	ByRef refImageElement As ImageElement,
	color As Color,
	colorTolerance As Byte,
	scanDirection As ScanDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim color As Color
Dim colorTolerance As Byte
Dim scanDirection As ScanDirectionImageDrawUtil.RemoveColor(refImageElement, 
	color, colorTolerance, scanDirection)
```

**C++**<br />
``` C++
public:
static void RemoveColor(
	ImageElement^% refImageElement, 
	Color color, 
	unsigned char colorTolerance, 
	ScanDirection scanDirection
)
```

**F#**<br />
``` F#
static member RemoveColor : 
        refImageElement : ImageElement byref * 
        color : Color * 
        colorTolerance : byte * 
        scanDirection : ScanDirection -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>color</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="color"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RemoveColor(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Byte,Neodynamic.SDK.ImageDraw.ScanDirection)"\]</dd><dt>colorTolerance</dt><dd>Type: System.Byte<br />\[Missing <param name="colorTolerance"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RemoveColor(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Byte,Neodynamic.SDK.ImageDraw.ScanDirection)"\]</dd><dt>scanDirection</dt><dd>Type: ScanDirection<br />\[Missing <param name="scanDirection"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RemoveColor(Neodynamic.SDK.ImageDraw.ImageElement@,System.Drawing.Color,System.Byte,Neodynamic.SDK.ImageDraw.ScanDirection)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />