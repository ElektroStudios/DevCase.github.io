# DrawingUtil.GetSquareSimilarityPercentage Method (Size)
 

Determine the similarity percentage that the specified Size has with a square shape, by dividing its shortest side between the longest one. 

 For example, having a Size of 4x4 (Width x Height), this function will return a value of 1, meaning that all the sides ( {Top=4, Bottom=4, Left=4, Right=4} ) are of equal length, or in other words, it is a perfect square shape. 

 For example too, having a Size of 640x480 (Width x Height), this function will return a value of 0.75, meaning that the length of the sides ( {Top=640, Bottom=640, Left=480, Right=480} ) are 75% near to be a perfect square shape.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double GetSquareSimilarityPercentage(
	Size size
)
```

**VB**<br />
``` VB
Public Shared Function GetSquareSimilarityPercentage ( 
	size As Size
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim size As Size
Dim returnValue As Double

returnValue = DrawingUtil.GetSquareSimilarityPercentage(size)
```

**C++**<br />
``` C++
public:
static double GetSquareSimilarityPercentage(
	Size size
)
```

**F#**<br />
``` F#
static member GetSquareSimilarityPercentage : 
        size : Size -> float 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Drawing.Size<br />The source Size.</dd></dl>

#### Return Value
Type: Double<br />The resulting similarity, expressed as a percentage value between 0 (as minimum) to 1.0 (as maximum).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim sz As New Size(width:=640, height:=480)
Dim prc As Double = GetSquareSimilarityPercentage(sz)
Dim str As String = String.Format("Square similarity of {0}: {1:P2}", sz.ToString(), prc, CultureInfo.InvariantCulture)

Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetSquareSimilarityPercentage">GetSquareSimilarityPercentage Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />