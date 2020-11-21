# ImageUtil.CompressImage Method (String, String, ImageFormat, Int32)
 

Compresses a image file to the specified filesize and saves the compressed image to disk.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CompressImage(
	string srcFilepath,
	string dstFilepath,
	ImageFormat newImageFormat,
	int newFileSize
)
```

**VB**<br />
``` VB
Public Shared Sub CompressImage ( 
	srcFilepath As String,
	dstFilepath As String,
	newImageFormat As ImageFormat,
	newFileSize As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFilepath As String
Dim dstFilepath As String
Dim newImageFormat As ImageFormat
Dim newFileSize As Integer

ImageUtil.CompressImage(srcFilepath, 
	dstFilepath, newImageFormat, newFileSize)
```

**C++**<br />
``` C++
public:
static void CompressImage(
	String^ srcFilepath, 
	String^ dstFilepath, 
	ImageFormat^ newImageFormat, 
	int newFileSize
)
```

**F#**<br />
``` F#
static member CompressImage : 
        srcFilepath : string * 
        dstFilepath : string * 
        newImageFormat : ImageFormat * 
        newFileSize : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>srcFilepath</dt><dd>Type: System.String<br />The source image filepath.</dd><dt>dstFilepath</dt><dd>Type: System.String<br />The target image filepath.</dd><dt>newImageFormat</dt><dd>Type: System.Drawing.Imaging.ImageFormat<br />The target image format.</dd><dt>newFileSize</dt><dd>Type: System.Int32<br />The target filesize, in bytes.</dd></dl>

## Examples
This is a code example that compress all JPG files in the specified directory. 
**VB**<br />
``` VB
' JPEG image files.
Dim imageFiles As IEnumerable(Of FileInfo) = New DirectoryInfo("C:\Images").EnumerateFiles("*.jpg", SearchOption.TopDirectoryOnly)
Dim compressedSize = 1048576 ' 1 Megabyte

For Each imgFile As FileInfo In imageFiles

    ImageUtil.CompressImage(imgFile.FullName, Path.ChangeExtension(imgFile.FullName, "compressed.jpg"), ImageFormat.Jpeg, compressedSize)
    Console.WriteLine($"Image Compressed: {imgFile.FullName}")

    '' Send old JPEG image to Recycle Bin.
    ' My.Computer.FileSystem.DeleteFile(imgFile.FullName, FileIO.UIOption.OnlyErrorDialogs, FileIO.RecycleOption.SendToRecycleBin)
Next imgFile
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_CompressImage">CompressImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />