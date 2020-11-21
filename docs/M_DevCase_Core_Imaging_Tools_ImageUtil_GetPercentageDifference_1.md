# ImageUtil.GetPercentageDifference Method (String, String, Byte)
 

Gets a value indicating the percentage of difference between two images.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetPercentageDifference(
	string imageFilepath1,
	string imageFilepath2,
	byte threshold
)
```

**VB**<br />
``` VB
Public Shared Function GetPercentageDifference ( 
	imageFilepath1 As String,
	imageFilepath2 As String,
	threshold As Byte
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim imageFilepath1 As String
Dim imageFilepath2 As String
Dim threshold As Byte
Dim returnValue As Single

returnValue = ImageUtil.GetPercentageDifference(imageFilepath1, 
	imageFilepath2, threshold)
```

**C++**<br />
``` C++
public:
static float GetPercentageDifference(
	String^ imageFilepath1, 
	String^ imageFilepath2, 
	unsigned char threshold
)
```

**F#**<br />
``` F#
static member GetPercentageDifference : 
        imageFilepath1 : string * 
        imageFilepath2 : string * 
        threshold : byte -> float32 

```


#### Parameters
&nbsp;<dl><dt>imageFilepath1</dt><dd>Type: System.String<br />The filepath of the first image to compare.</dd><dt>imageFilepath2</dt><dd>Type: System.String<br />The filepath of the second image to compare with *imageFilepath1*.</dd><dt>threshold</dt><dd>Type: System.Byte<br />A value from `0` to `255` indicating how big a difference will be ignored.</dd></dl>

#### Return Value
Type: Single<br />The resulting percentage difference value between the two specified images.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = "C:\Image1.jpg"
Dim img2 As Image = "C:\Image2.jpg"
Dim threshold As Integer = 1

Dim percentDiff As String =
    String.Format("Percentage Difference: {0:0.00}%",
                  GetPercentageDifference(img1, img2, threshold))

MessageBox.Show(percentDiff)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetPercentageDifference">GetPercentageDifference Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />