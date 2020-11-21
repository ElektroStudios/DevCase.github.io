# ImageDrawUtil.RoundCorners Method (ImageElement, Corners, Int32, Int32, Color)
 

Rounds image corners.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RoundCorners(
	ref ImageElement refImageElement,
	Corners corners,
	int roundness,
	int borderWidth,
	Color borderColor
)
```

**VB**<br />
``` VB
Public Shared Sub RoundCorners ( 
	ByRef refImageElement As ImageElement,
	corners As Corners,
	roundness As Integer,
	borderWidth As Integer,
	borderColor As Color
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim corners As Corners
Dim roundness As Integer
Dim borderWidth As Integer
Dim borderColor As ColorImageDrawUtil.RoundCorners(refImageElement, 
	corners, roundness, borderWidth, 
	borderColor)
```

**C++**<br />
``` C++
public:
static void RoundCorners(
	ImageElement^% refImageElement, 
	Corners corners, 
	int roundness, 
	int borderWidth, 
	Color borderColor
)
```

**F#**<br />
``` F#
static member RoundCorners : 
        refImageElement : ImageElement byref * 
        corners : Corners * 
        roundness : int * 
        borderWidth : int * 
        borderColor : Color -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>corners</dt><dd>Type: Corners<br />\[Missing <param name="corners"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RoundCorners(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.Corners,System.Int32,System.Int32,System.Drawing.Color)"\]</dd><dt>roundness</dt><dd>Type: System.Int32<br />\[Missing <param name="roundness"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RoundCorners(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.Corners,System.Int32,System.Int32,System.Drawing.Color)"\]</dd><dt>borderWidth</dt><dd>Type: System.Int32<br />\[Missing <param name="borderWidth"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RoundCorners(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.Corners,System.Int32,System.Int32,System.Drawing.Color)"\]</dd><dt>borderColor</dt><dd>Type: System.Drawing.Color<br />\[Missing <param name="borderColor"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.RoundCorners(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.Corners,System.Int32,System.Int32,System.Drawing.Color)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_ImageDraw_ImageDrawUtil_RoundCorners">RoundCorners Overload</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />