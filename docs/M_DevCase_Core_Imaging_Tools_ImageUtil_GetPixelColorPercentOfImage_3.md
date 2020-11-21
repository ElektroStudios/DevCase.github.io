# ImageUtil.GetPixelColorPercentOfImage Method (FileInfo, Int32, Color)
 

Analyzes each pixel of the spcified image, counts all the pixels that are of same color as the color specified, then calculates a percentage of the total grayscale presence in the image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetPixelColorPercentOfImage(
	FileInfo file,
	int dimensionIndex,
	Color color
)
```

**VB**<br />
``` VB
Public Shared Function GetPixelColorPercentOfImage ( 
	file As FileInfo,
	dimensionIndex As Integer,
	color As Color
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim dimensionIndex As Integer
Dim color As Color
Dim returnValue As Double

returnValue = ImageUtil.GetPixelColorPercentOfImage(file, 
	dimensionIndex, color)
```

**C++**<br />
``` C++
public:
static double GetPixelColorPercentOfImage(
	FileInfo^ file, 
	int dimensionIndex, 
	Color color
)
```

**F#**<br />
``` F#
static member GetPixelColorPercentOfImage : 
        file : FileInfo * 
        dimensionIndex : int * 
        color : Color -> float 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The image file.</dd><dt>dimensionIndex</dt><dd>Type: System.Int32<br />The index of the image dimension to analyze.</dd><dt>color</dt><dd>Type: System.Drawing.Color<br />The color.</dd></dl>

#### Return Value
Type: Double<br />The resulting percentage of pixels in the source image that are of same color as the color specified.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\Image.jpg")
Dim color As Color = Color.FromArgb(255, 255, 255, 255)
Dim percent As Double = GetGrayScalePixelPercentOfImage(file, dimensionIndex:=0, color:=color)
Dim strFormat As String = String.Format("{0:F2}%", percent)

Console.WriteLine(strFormat)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetPixelColorPercentOfImage">GetPixelColorPercentOfImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />