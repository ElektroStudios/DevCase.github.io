# ImageDrawUtil.CameraView Method 
 

Simulates the camera view on an element.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CameraView(
	ref ImageElement refImageElement,
	int verticalRotationAngle,
	int horizontalRotationAngle
)
```

**VB**<br />
``` VB
Public Shared Sub CameraView ( 
	ByRef refImageElement As ImageElement,
	verticalRotationAngle As Integer,
	horizontalRotationAngle As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim refImageElement As ImageElement
Dim verticalRotationAngle As Integer
Dim horizontalRotationAngle As Integer

ImageDrawUtil.CameraView(refImageElement, 
	verticalRotationAngle, horizontalRotationAngle)
```

**C++**<br />
``` C++
public:
static void CameraView(
	ImageElement^% refImageElement, 
	int verticalRotationAngle, 
	int horizontalRotationAngle
)
```

**F#**<br />
``` F#
static member CameraView : 
        refImageElement : ImageElement byref * 
        verticalRotationAngle : int * 
        horizontalRotationAngle : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>refImageElement</dt><dd>Type: ImageElement<br />The image draw element.</dd><dt>verticalRotationAngle</dt><dd>Type: System.Int32<br />\[Missing <param name="verticalRotationAngle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.CameraView(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd><dt>horizontalRotationAngle</dt><dd>Type: System.Int32<br />\[Missing <param name="horizontalRotationAngle"/> documentation for "M:DevCase.ThirdParty.ImageDraw.ImageDrawUtil.CameraView(Neodynamic.SDK.ImageDraw.ImageElement@,System.Int32,System.Int32)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ImageDraw_ImageDrawUtil">ImageDrawUtil Class</a><br /><a href="N_DevCase_ThirdParty_ImageDraw">DevCase.ThirdParty.ImageDraw Namespace</a><br />