# ImageUtil.ConvertImageFile Method (String, String, BitmapEncoder)
 

Converts a image file to a different image format and saves the converted image to disk.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ConvertImageFile(
	string srcFile,
	string dstFile,
	BitmapEncoder encoder
)
```

**VB**<br />
``` VB
Public Shared Sub ConvertImageFile ( 
	srcFile As String,
	dstFile As String,
	encoder As BitmapEncoder
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFile As String
Dim dstFile As String
Dim encoder As BitmapEncoderImageUtil.ConvertImageFile(srcFile, dstFile, 
	encoder)
```

**C++**<br />
``` C++
public:
static void ConvertImageFile(
	String^ srcFile, 
	String^ dstFile, 
	BitmapEncoder^ encoder
)
```

**F#**<br />
``` F#
static member ConvertImageFile : 
        srcFile : string * 
        dstFile : string * 
        encoder : BitmapEncoder -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.String<br />The source image file path.</dd><dt>dstFile</dt><dd>Type: System.String<br />The destination image file path.</dd><dt>encoder</dt><dd>Type: System.Windows.Media.Imaging.BitmapEncoder<br />A BitmapEncoder instance (BmpBitmapEncoder, GifBitmapEncoder, JpegBitmapEncoder, PngBitmapEncoder or TiffBitmapEncoder) that represents the encoder and its parameters.</dd></dl>

## Examples
This is a code example that converts PNG files to JPEG format. 
**VB**<br />
``` VB
' PNG image files.
Dim imageFiles As IEnumerable(Of FileInfo) = New DirectoryInfo("C:\Images").EnumerateFiles("*.png", SearchOption.TopDirectoryOnly)

For Each imgFile As FileInfo In imageFiles
    ' Convert PNG image to JPEG.
    ConvertImageFile(imgFile.FullName, Path.ChangeExtension(imgFile.FullName, "jpg"), New JpegBitmapEncoder With {.QualityLevel = 95})
    Console.WriteLine($"Image Converted: {imgFile.FullName}")

    '' Send old PNG image to Recycle Bin.
    ' My.Computer.FileSystem.DeleteFile(imgFile.FullName, FileIO.UIOption.OnlyErrorDialogs, FileIO.RecycleOption.SendToRecycleBin)
Next imgFile
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_ConvertImageFile">ConvertImageFile Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />