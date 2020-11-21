# FreeImageUtil.GrayScale Method (Bitmap)
 

Grayscales the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap GrayScale(
	Bitmap bmp
)
```

**VB**<br />
``` VB
Public Shared Function GrayScale ( 
	bmp As Bitmap
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim returnValue As Bitmap

returnValue = FreeImageUtil.GrayScale(bmp)
```

**C++**<br />
``` C++
public:
static Bitmap^ GrayScale(
	Bitmap^ bmp
)
```

**F#**<br />
``` F#
static member GrayScale : 
        bmp : Bitmap -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_GrayScale">GrayScale Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />