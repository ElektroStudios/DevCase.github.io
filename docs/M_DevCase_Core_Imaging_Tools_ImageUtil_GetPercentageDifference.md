# ImageUtil.GetPercentageDifference Method (Image, Image, Byte)
 

Gets a value indicating the percentage of difference between two images.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetPercentageDifference(
	Image img1,
	Image img2,
	byte threshold
)
```

**VB**<br />
``` VB
Public Shared Function GetPercentageDifference ( 
	img1 As Image,
	img2 As Image,
	threshold As Byte
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim img1 As Image
Dim img2 As Image
Dim threshold As Byte
Dim returnValue As Single

returnValue = ImageUtil.GetPercentageDifference(img1, 
	img2, threshold)
```

**C++**<br />
``` C++
public:
static float GetPercentageDifference(
	Image^ img1, 
	Image^ img2, 
	unsigned char threshold
)
```

**F#**<br />
``` F#
static member GetPercentageDifference : 
        img1 : Image * 
        img2 : Image * 
        threshold : byte -> float32 

```


#### Parameters
&nbsp;<dl><dt>img1</dt><dd>Type: System.Drawing.Image<br />The first image to compare.</dd><dt>img2</dt><dd>Type: System.Drawing.Image<br />The second image to compare with *img1*.</dd><dt>threshold</dt><dd>Type: System.Byte<br />A value from `0` to `255` indicating how big a difference will be ignored.</dd></dl>

#### Return Value
Type: Single<br />The resulting percentage difference value between the two specified images. 

 A value of 0 (zero) means the images are equal; a value of 1 (one) means the images are totally different.

## Remarks
<a href="http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET" target="_blank">http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = Image.FromFile("C:\Image1.jpg")
Dim img2 As Image = Image.FromFile("C:\Image2.jpg")
Dim threshold As Integer = 1

Dim percentDiff As String =
    String.Format("Percentage Difference: {0:0.00}%",
                  GetPercentageDifference(img1, img2, threshold) * 100)

MessageBox.Show(percentDiff)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_GetPercentageDifference">GetPercentageDifference Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />