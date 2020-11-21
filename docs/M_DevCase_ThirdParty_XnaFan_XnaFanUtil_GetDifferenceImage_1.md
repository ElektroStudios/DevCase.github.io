# XnaFanUtil.GetDifferenceImage Method (String, String)
 

Gets an Image which displays the differences between two images.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image GetDifferenceImage(
	string imageFilepath1,
	string imageFilepath2
)
```

**VB**<br />
``` VB
Public Shared Function GetDifferenceImage ( 
	imageFilepath1 As String,
	imageFilepath2 As String
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim imageFilepath1 As String
Dim imageFilepath2 As String
Dim returnValue As Image

returnValue = XnaFanUtil.GetDifferenceImage(imageFilepath1, 
	imageFilepath2)
```

**C++**<br />
``` C++
public:
static Image^ GetDifferenceImage(
	String^ imageFilepath1, 
	String^ imageFilepath2
)
```

**F#**<br />
``` F#
static member GetDifferenceImage : 
        imageFilepath1 : string * 
        imageFilepath2 : string -> Image 

```


#### Parameters
&nbsp;<dl><dt>imageFilepath1</dt><dd>Type: System.String<br />The filepath of the first image to compare.</dd><dt>imageFilepath2</dt><dd>Type: System.String<br />The filepath of the second image to compare.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = "C:\Image1.jpg"
Dim img2 As Image = "C:\Image2.jpg"

Dim imageDiff As Image = GetDifferenceImage(img1, img2)

PictureBox1.BackgroundImage = imageDiff
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_XnaFan_XnaFanUtil">XnaFanUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_XnaFan_XnaFanUtil_GetDifferenceImage">GetDifferenceImage Overload</a><br /><a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan Namespace</a><br />