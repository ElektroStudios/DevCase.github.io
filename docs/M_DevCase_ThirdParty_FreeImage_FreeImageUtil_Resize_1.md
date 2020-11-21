# FreeImageUtil.Resize Method (Bitmap, Int32, Int32, FREE_IMAGE_FILTER)
 

Resizes the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap Resize(
	Bitmap bmp,
	int width,
	int height,
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER.FILTER_BILINEAR
)
```

**VB**<br />
``` VB
Public Shared Function Resize ( 
	bmp As Bitmap,
	width As Integer,
	height As Integer,
	Optional quality As FREE_IMAGE_FILTER = FREE_IMAGE_FILTER.FILTER_BILINEAR
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim width As Integer
Dim height As Integer
Dim quality As FREE_IMAGE_FILTER
Dim returnValue As Bitmap

returnValue = FreeImageUtil.Resize(bmp, width, 
	height, quality)
```

**C++**<br />
``` C++
public:
static Bitmap^ Resize(
	Bitmap^ bmp, 
	int width, 
	int height, 
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER::FILTER_BILINEAR
)
```

**F#**<br />
``` F#
static member Resize : 
        bmp : Bitmap * 
        width : int * 
        height : int * 
        ?quality : FREE_IMAGE_FILTER 
(* Defaults:
        let _quality = defaultArg quality FREE_IMAGE_FILTER.FILTER_BILINEAR
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>width</dt><dd>Type: System.Int32<br />The new width.</dd><dt>height</dt><dd>Type: System.Int32<br />The new height.</dd><dt>quality (Optional)</dt><dd>Type: FREE_IMAGE_FILTER<br />The resize quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize">Resize Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />