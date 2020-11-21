# ImageUtil.GetPixelColorPercentOfImage Method (Image, Color)
 

Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetPixelColorPercentOfImage(
	Image img,
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelColorPercentOfImage ( 
	img As Image,
	color As Color
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim color As Color
Dim returnValue As Double

returnValue = ImageUtil.GetPixelColorPercentOfImage(img, 
	color)
```

**C++**<br />
``` C++
public:
static double GetPixelColorPercentOfImage(
	Image^ img, 
	Color color
)
```

**F#**<br />
``` F#
static member GetPixelColorPercentOfImage : 
        img : Image * 
        color : Color -> float 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: System.Drawing.Image<br />The source image.</dd><dt>color</dt><dd>Type: System.Drawing.Color<br />The color.</dd></dl>

#### Return Value
Type: Double<br />The resulting percentage of pixels in the source image that are of same color as the color specified.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim color As Color = Color.FromArgb(255, 255, 255, 255)

For Each file As FileInfo In New DirectoryInfo("C:\Images").EnumerateFiles("*.gif", SearchOption.TopDirectoryOnly)

    Using img As Image = Image.FromFile(file.FullName)
        Dim percent As Double = GetGrayScalePixelPercentOfImage(img, color)
        Dim strFormat As String = String.Format("[{0,6:F2} %]: {1}", percent, file.Name)

        Console.WriteLine(strFormat)
    End Using

Next file
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage">GetPixelColorPercentOfImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />