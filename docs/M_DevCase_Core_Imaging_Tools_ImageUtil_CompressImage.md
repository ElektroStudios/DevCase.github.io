# ImageUtil.CompressImage Method (String, ImageFormat, Int32)
 

Compresses a image file to the specified filesize and returns the raw image stream of the compressed image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MemoryStream CompressImage(
	string srcFilepath,
	ImageFormat newImageFormat,
	int newFileSize
)
```

**VB**<br />
``` VB
Public Shared Function CompressImage ( 
	srcFilepath As String,
	newImageFormat As ImageFormat,
	newFileSize As Integer
) As MemoryStream
```

**VB Usage**<br />
``` VB Usage
Dim srcFilepath As String
Dim newImageFormat As ImageFormat
Dim newFileSize As Integer
Dim returnValue As MemoryStream

returnValue = ImageUtil.CompressImage(srcFilepath, 
	newImageFormat, newFileSize)
```

**C++**<br />
``` C++
public:
static MemoryStream^ CompressImage(
	String^ srcFilepath, 
	ImageFormat^ newImageFormat, 
	int newFileSize
)
```

**F#**<br />
``` F#
static member CompressImage : 
        srcFilepath : string * 
        newImageFormat : ImageFormat * 
        newFileSize : int -> MemoryStream 

```


#### Parameters
&nbsp;<dl><dt>srcFilepath</dt><dd>Type: System.String<br />The source image filepath.</dd><dt>newImageFormat</dt><dd>Type: System.Drawing.Imaging.ImageFormat<br />The target image format.</dd><dt>newFileSize</dt><dd>Type: System.Int32<br />The target filesize, in bytes.</dd></dl>

#### Return Value
Type: MemoryStream<br />\[Missing <returns> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.CompressImage(System.String,System.Drawing.Imaging.ImageFormat,System.Int32)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim imageFile As String = "C:\Image.jpg"
Dim compressedSize = 1048576 ' 1 Megabyte

Dim compressedImage As MemoryStream = ImageUtil.CompressImage(imageFile, ImageFormat.Jpeg, compressedSize)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_CompressImage">CompressImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />