# ImageUtil.ConvertImageFile Method (String, BitmapEncoder)
 

Converts a image file to a different image format and returns the raw image stream of the converted image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MemoryStream ConvertImageFile(
	string srcFile,
	BitmapEncoder encoder
)
```

**VB**<br />
``` VB
Public Shared Function ConvertImageFile ( 
	srcFile As String,
	encoder As BitmapEncoder
) As MemoryStream
```

**VB Usage**<br />
``` VB Usage
Dim srcFile As String
Dim encoder As BitmapEncoder
Dim returnValue As MemoryStream

returnValue = ImageUtil.ConvertImageFile(srcFile, 
	encoder)
```

**C++**<br />
``` C++
public:
static MemoryStream^ ConvertImageFile(
	String^ srcFile, 
	BitmapEncoder^ encoder
)
```

**F#**<br />
``` F#
static member ConvertImageFile : 
        srcFile : string * 
        encoder : BitmapEncoder -> MemoryStream 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.String<br />The source image file path.</dd><dt>encoder</dt><dd>Type: System.Windows.Media.Imaging.BitmapEncoder<br />A BitmapEncoder instance (BmpBitmapEncoder, GifBitmapEncoder, JpegBitmapEncoder, PngBitmapEncoder or TiffBitmapEncoder) that represents the encoder and its parameters.</dd></dl>

#### Return Value
Type: MemoryStream<br />\[Missing <returns> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.ConvertImageFile(System.String,System.Windows.Media.Imaging.BitmapEncoder)"\]

## Examples
This is a code example that converts PNG files to JPEG format. 
**VB**<br />
``` VB
Dim imageFile As String = "C:\Image.jpg"
Dim convertedImage As MemoryStream = ImageUtil.ConvertImageFile(imageFile, New JpegBitmapEncoder With {.QualityLevel = 95})
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_ConvertImageFile">ConvertImageFile Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />