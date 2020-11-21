# FreeImageUtil.Resize Method (String, Int32, Int32, FREE_IMAGE_FILTER)
 

Resizes the specified image file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap Resize(
	string filepath,
	int width,
	int height,
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER.FILTER_BILINEAR
)
```

**VB**<br />
``` VB
Public Shared Function Resize ( 
	filepath As String,
	width As Integer,
	height As Integer,
	Optional quality As FREE_IMAGE_FILTER = FREE_IMAGE_FILTER.FILTER_BILINEAR
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim width As Integer
Dim height As Integer
Dim quality As FREE_IMAGE_FILTER
Dim returnValue As Bitmap

returnValue = FreeImageUtil.Resize(filepath, 
	width, height, quality)
```

**C++**<br />
``` C++
public:
static Bitmap^ Resize(
	String^ filepath, 
	int width, 
	int height, 
	FREE_IMAGE_FILTER quality = FREE_IMAGE_FILTER::FILTER_BILINEAR
)
```

**F#**<br />
``` F#
static member Resize : 
        filepath : string * 
        width : int * 
        height : int * 
        ?quality : FREE_IMAGE_FILTER 
(* Defaults:
        let _quality = defaultArg quality FREE_IMAGE_FILTER.FILTER_BILINEAR
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source image filepath.</dd><dt>width</dt><dd>Type: System.Int32<br />The new width.</dd><dt>height</dt><dd>Type: System.Int32<br />The new height.</dd><dt>quality (Optional)</dt><dd>Type: FREE_IMAGE_FILTER<br />The resize quality.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_Resize">Resize Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />