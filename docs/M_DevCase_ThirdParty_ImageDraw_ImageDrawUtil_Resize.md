# ImageDrawUtil.Resize Method 
 

Changes the size of an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Resize(
	ref ImageElement refImageElement,
	int width,
	int height,
	LockAspectRatio lockAspectRatio,
	InterpolationMode interpolationMode
)
```

**VB**<br />
``` VB
Public Shared Sub Resize ( 
	ByRef refImageElement As ImageElement,
	width As Integer,
	height As Integer,
	lockAspectRatio As LockAspectRatio,
	interpolationMode As InterpolationMode
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim width As Integer
Dim height As Integer
Dim lockAspectRatio As LockAspectRatio
Dim interpolationMode As InterpolationModeImageDrawUtil.Resize(refImageElement, width, 
	height, lockAspectRatio, interpolationMode)
```

**C++**<br />
``` C++
public:
static void Resize(
	ImageElement^% refImageElement, 
	int width, 
	int height, 
	LockAspectRatio lockAspectRatio, 
	InterpolationMode interpolationMode
)
```

**F#**<br />
``` F#
static member Resize : 
        refImageElement : ImageElement byref * 
        width : int * 
        height : int * 
        lockAspectRatio : LockAspectRatio * 
        interpolationMode : InterpolationMode -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>width</dt><dd>Type: System.Int32<br />\[Missing <param name="width"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Resize(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.LockAspectRatio,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>height</dt><dd>Type: System.Int32<br />\[Missing <param name="height"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Resize(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.LockAspectRatio,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>lockAspectRatio</dt><dd>Type: LockAspectRatio<br />\[Missing <param name="lockAspectRatio"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Resize(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.LockAspectRatio,System.Drawing.Drawing2D.InterpolationMode)"\]</dd><dt>interpolationMode</dt><dd>Type: System.Drawing.Drawing2D.InterpolationMode<br />\[Missing <param name="interpolationMode"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.Resize(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32,Neodynamic.SDK.ImageDraw.LockAspectRatio,System.Drawing.Drawing2D.InterpolationMode)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />