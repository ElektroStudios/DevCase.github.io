# FreeImageUtil.Resize Method (Bitmap, Size, FREE_IMAGE_FILTER)
 

Resizes the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap Resize(
	Bitmap bmp,
	Size size,
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER.FILTER_BILINEAR
)
```

**VB**<br />
``` VB
Public Shared Function Resize ( 
	bmp As Bitmap,
	size As Size,
	Optional quality As FREE_IMAGE_FILTER = FREE_IMAGE_FILTER.FILTER_BILINEAR
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim size As Size
Dim quality As FREE_IMAGE_FILTER
Dim returnValue As Bitmap

returnValue = FreeImageUtil.Resize(bmp, size, 
	quality)
```

**C++**<br />
``` C++
public:
static Bitmap^ Resize(
	Bitmap^ bmp, 
	Size size, 
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER::FILTER_BILINEAR
)
```

**F#**<br />
``` F#
static member Resize : 
        bmp : Bitmap * 
        size : Size * 
        ?quality : FREE_IMAGE_FILTER 
(* Defaults:
        let _quality = defaultArg quality FREE_IMAGE_FILTER.FILTER_BILINEAR
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The new size.</dd><dt>quality (Optional)</dt><dd>Type: FREE_IMAGE_FILTER<br />The resize quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize">Resize Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />