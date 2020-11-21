# ImageDrawUtil.DistortCorners Method 
 

Distorts an element by changing the coordinates of the four corners defined by the element's boundaries.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DistortCorners(
	ref ImageElement refImageElement,
	int x1,
	int y1,
	int x2,
	int y2,
	int x3,
	int y3,
	int x4,
	int y4
)
```

**VB**<br />
``` VB
Public Shared Sub DistortCorners ( 
	ByRef refImageElement As ImageElement,
	x1 As Integer,
	y1 As Integer,
	x2 As Integer,
	y2 As Integer,
	x3 As Integer,
	y3 As Integer,
	x4 As Integer,
	y4 As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim x1 As Integer
Dim y1 As Integer
Dim x2 As Integer
Dim y2 As Integer
Dim x3 As Integer
Dim y3 As Integer
Dim x4 As Integer
Dim y4 As Integer

ImageDrawUtil.DistortCorners(refImageElement, 
	x1, y1, x2, y2, x3, y3, x4, y4)
```

**C++**<br />
``` C++
public:
static void DistortCorners(
	ImageElement^% refImageElement, 
	int x1, 
	int y1, 
	int x2, 
	int y2, 
	int x3, 
	int y3, 
	int x4, 
	int y4
)
```

**F#**<br />
``` F#
static member DistortCorners : 
        refImageElement : ImageElement byref * 
        x1 : int * 
        y1 : int * 
        x2 : int * 
        y2 : int * 
        x3 : int * 
        y3 : int * 
        x4 : int * 
        y4 : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>x1</dt><dd>Type: System.Int32<br />\[Missing <param name="x1"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>y1</dt><dd>Type: System.Int32<br />\[Missing <param name="y1"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>x2</dt><dd>Type: System.Int32<br />\[Missing <param name="x2"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>y2</dt><dd>Type: System.Int32<br />\[Missing <param name="y2"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>x3</dt><dd>Type: System.Int32<br />\[Missing <param name="x3"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>y3</dt><dd>Type: System.Int32<br />\[Missing <param name="y3"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>x4</dt><dd>Type: System.Int32<br />\[Missing <param name="x4"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd><dt>y4</dt><dd>Type: System.Int32<br />\[Missing <param name="y4"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.DistortCorners(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />