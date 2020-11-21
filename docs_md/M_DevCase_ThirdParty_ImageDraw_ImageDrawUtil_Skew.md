# ImageDrawUtil.Skew Method 
 

Skews an element. Skewing an element transforms it by slanting it along the horizontal or vertical axis. When skewed, an element pivots on its origin point.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Skew(
	ref ImageElement refImageElement,
	SkewType type,
	int angle,
	SkewOrientation orientation,
	bool constrainProportions
)
```

**VB**<br />
``` VB
Public Shared Sub Skew ( 
	ByRef refImageElement As ImageElement,
	type As SkewType,
	angle As Integer,
	orientation As SkewOrientation,
	constrainProportions As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim type As SkewType
Dim angle As Integer
Dim orientation As SkewOrientation
Dim constrainProportions As BooleanImageDrawUtil.Skew(refImageElement, type, 
	angle, orientation, constrainProportions)
```

**C++**<br />
``` C++
public:
static void Skew(
	ImageElement^% refImageElement, 
	SkewType type, 
	int angle, 
	SkewOrientation orientation, 
	bool constrainProportions
)
```

**F#**<br />
``` F#
static member Skew : 
        refImageElement : ImageElement byref * 
        type : SkewType * 
        angle : int * 
        orientation : SkewOrientation * 
        constrainProportions : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>type</dt><dd>Type: SkewType<br />\[Missing <param name="type"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Skew(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.SkewType,System.Int32,Neodynamic.SDK.ImageDraw.SkewOrientation,System.Boolean)"\]</dd><dt>angle</dt><dd>Type: System.Int32<br />\[Missing <param name="angle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Skew(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.SkewType,System.Int32,Neodynamic.SDK.ImageDraw.SkewOrientation,System.Boolean)"\]</dd><dt>orientation</dt><dd>Type: SkewOrientation<br />\[Missing <param name="orientation"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Skew(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.SkewType,System.Int32,Neodynamic.SDK.ImageDraw.SkewOrientation,System.Boolean)"\]</dd><dt>constrainProportions</dt><dd>Type: System.Boolean<br />\[Missing <param name="constrainProportions"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Skew(Neodynamic.SDK.ImageDraw.ImageElement@,Neodynamic.SDK.ImageDraw.SkewType,System.Int32,Neodynamic.SDK.ImageDraw.SkewOrientation,System.Boolean)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />