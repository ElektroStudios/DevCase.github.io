# ImageUtil.GetDifferences Method 
 

Finds the RGB differences between two images and returns them in a two-dimensional Array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[,] GetDifferences(
	Image img1,
	Image img2
)
```

**VB**<br />
``` VB
Public Shared Function GetDifferences ( 
	img1 As Image,
	img2 As Image
) As Byte(,)
```

**VB Usage**<br />
``` VB Usage
Dim img1 As Image
Dim img2 As Image
Dim returnValue As Byte(,)

returnValue = ImageUtil.GetDifferences(img1, 
	img2)
```

**C++**<br />
``` C++
public:
static array<unsigned char,2>^ GetDifferences(
	Image^ img1, 
	Image^ img2
)
```

**F#**<br />
``` F#
static member GetDifferences : 
        img1 : Image * 
        img2 : Image -> byte[,] 

```


#### Parameters
&nbsp;<dl><dt>img1</dt><dd>Type: System.Drawing.Image<br />The first image to compare.</dd><dt>img2</dt><dd>Type: System.Drawing.Image<br />The second image to compare with *img1*.</dd></dl>

#### Return Value
Type: Byte[,]<br />The RGB differences between the two specified images.

## Remarks
<a href="http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET" target="_blank">http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />