# ImageUtil.GetGrayScalePixelPercentOfImage Method (String)
 

Analyzes each pixel of the spcified image, counts all the pixels that are within the grayscale RGB range, then calculates a percentage of the total grayscale presence in the image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetGrayScalePixelPercentOfImage(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetGrayScalePixelPercentOfImage ( 
	filepath As String
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Double

returnValue = ImageUtil.GetGrayScalePixelPercentOfImage(filepath)
```

**C++**<br />
``` C++
public:
static double GetGrayScalePixelPercentOfImage(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetGrayScalePixelPercentOfImage : 
        filepath : string -> float 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The image file path.</dd></dl>

#### Return Value
Type: Double<br />The resulting percentage of grayscale pixels in the source image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filepath As String = "C:\Image.jpg"
Dim percent As Double = GetGrayScalePixelPercentOfImage(filepath)
Dim strFormat As String = String.Format("{0:F2}%", percent)

Console.WriteLine(strFormat)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetGrayScalePixelPercentOfImage">GetGrayScalePixelPercentOfImage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />