# ImageUtil.GetGrayScalePixelPercentOfImage Method (Image, Int32)
 

Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetGrayScalePixelPercentOfImage(
	Image img,
	int dimensionIndex
)
```

**VB**<br />
``` VB
Public Shared Function GetGrayScalePixelPercentOfImage ( 
	img As Image,
	dimensionIndex As Integer
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim dimensionIndex As Integer
Dim returnValue As Double

returnValue = ImageUtil.GetGrayScalePixelPercentOfImage(img, 
	dimensionIndex)
```

**C++**<br />
``` C++
public:
static double GetGrayScalePixelPercentOfImage(
	Image^ img, 
	int dimensionIndex
)
```

**F#**<br />
``` F#
static member GetGrayScalePixelPercentOfImage : 
        img : Image * 
        dimensionIndex : int -> float 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: System.Drawing.Image<br />The source image.</dd><dt>dimensionIndex</dt><dd>Type: System.Int32<br />The index of the image dimension to analyze.</dd></dl>

#### Return Value
Type: Double<br />The resulting percentage of grayscale pixels in the source image.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each file As FileInfo In New DirectoryInfo("C:\Images").EnumerateFiles("*.gif", SearchOption.TopDirectoryOnly)

    Using img As Image = Image.FromFile(file.FullName)
        Dim percent As Double = GetGrayScalePixelPercentOfImage(img, dimensionIndex:=0)
        Dim strFormat As String = String.Format("[{0,6:F2} %]: {1}", percent, file.Name)

        Console.WriteLine(strFormat)
    End Using

Next file
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage">GetGrayScalePixelPercentOfImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />