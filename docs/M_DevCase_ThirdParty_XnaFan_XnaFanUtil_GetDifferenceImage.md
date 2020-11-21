# XnaFanUtil.GetDifferenceImage Method (Image, Image)
 

Gets an Image which displays the differences between two images.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image GetDifferenceImage(
	Image image1,
	Image image2
)
```

**VB**<br />
``` VB
Public Shared Function GetDifferenceImage ( 
	image1 As Image,
	image2 As Image
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim image1 As Image
Dim image2 As Image
Dim returnValue As Image

returnValue = XnaFanUtil.GetDifferenceImage(image1, 
	image2)
```

**C++**<br />
``` C++
public:
static Image^ GetDifferenceImage(
	Image^ image1, 
	Image^ image2
)
```

**F#**<br />
``` F#
static member GetDifferenceImage : 
        image1 : Image * 
        image2 : Image -> Image 

```


#### Parameters
&nbsp;<dl><dt>image1</dt><dd>Type: System.Drawing.Image<br />The first image to compare.</dd><dt>image2</dt><dd>Type: System.Drawing.Image<br />The second image to compare.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = Image.FromFile("C:\Image1.jpg")
Dim img2 As Image = Image.FromFile("C:\Image2.jpg")

Dim imageDiff As Image = GetDifferenceImage(img1, img2)

PictureBox1.BackgroundImage = imageDiff
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_XnaFan_XnaFanUtil">XnaFanUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_XnaFan_XnaFanUtil_GetDifferenceImage">GetDifferenceImage Overload</a><br /><a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan Namespace</a><br />