# XnaFanUtil.GetDifferenceValue Method (Image, Image, Int32)
 

Gets a value indicating the percentage of difference between two images.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetDifferenceValue(
	Image image1,
	Image image2,
	int threshold = 1
)
```

**VB**<br />
``` VB
Public Shared Function GetDifferenceValue ( 
	image1 As Image,
	image2 As Image,
	Optional threshold As Integer = 1
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim image1 As Image
Dim image2 As Image
Dim threshold As Integer
Dim returnValue As Single

returnValue = XnaFanUtil.GetDifferenceValue(image1, 
	image2, threshold)
```

**C++**<br />
``` C++
public:
static float GetDifferenceValue(
	Image^ image1, 
	Image^ image2, 
	int threshold = 1
)
```

**F#**<br />
``` F#
static member GetDifferenceValue : 
        image1 : Image * 
        image2 : Image * 
        ?threshold : int 
(* Defaults:
        let _threshold = defaultArg threshold 1
*)
-> float32 

```


#### Parameters
&nbsp;<dl><dt>image1</dt><dd>Type: System.Drawing.Image<br />The first image to compare.</dd><dt>image2</dt><dd>Type: System.Drawing.Image<br />The second image to compare.</dd><dt>threshold (Optional)</dt><dd>Type: System.Int32<br />A value, from `0` to `100`, indicating how big a difference will be ignored. 

 Default value is `1`.</dd></dl>

#### Return Value
Type: Single<br />The resulting percentage value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = Image.FromFile("C:\Image1.jpg")
Dim img2 As Image = Image.FromFile("C:\Image2.jpg")
Dim threshold As Integer = 1

Dim percentDiff As String =
    String.Format("Percentage Difference: {0:0.00}%",
                  GetDifferenceValue(img1, img2, threshold))

MessageBox.Show(percentDiff)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_XnaFan_XnaFanUtil">XnaFanUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_XnaFan_XnaFanUtil_GetDifferenceValue">GetDifferenceValue Overload</a><br /><a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan Namespace</a><br />