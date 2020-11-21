# ImageUtil.CreateSolidcolorBitmap Method 
 

Creates a Bitmap image which is filled with the specified solid color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap CreateSolidcolorBitmap(
	Size size,
	Color fillColor,
	PixelFormat pixelFormat = PixelFormat.Format32bppArgb
)
```

**VB**<br />
``` VB
Public Shared Function CreateSolidcolorBitmap ( 
	size As Size,
	fillColor As Color,
	Optional pixelFormat As PixelFormat = PixelFormat.Format32bppArgb
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim size As Size
Dim fillColor As Color
Dim pixelFormat As PixelFormat
Dim returnValue As Bitmap

returnValue = ImageUtil.CreateSolidcolorBitmap(size, 
	fillColor, pixelFormat)
```

**C++**<br />
``` C++
public:
static Bitmap^ CreateSolidcolorBitmap(
	Size size, 
	Color fillColor, 
	PixelFormat pixelFormat = PixelFormat::Format32bppArgb
)
```

**F#**<br />
``` F#
static member CreateSolidcolorBitmap : 
        size : Size * 
        fillColor : Color * 
        ?pixelFormat : PixelFormat 
(* Defaults:
        let _pixelFormat = defaultArg pixelFormat PixelFormat.Format32bppArgb
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Drawing.Size<br />The size of the Bitmap.</dd><dt>fillColor</dt><dd>Type: System.Drawing.Color<br />The Color to fill the Bitmap.</dd><dt>pixelFormat (Optional)</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The format of the color data for each pixel in the image.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting Bitmap image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim bmp As Bitmap = CreateSolidcolorBitmap(New Size(256, 256), Color.Teal, PixelFormat.Format32bppArgb)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />