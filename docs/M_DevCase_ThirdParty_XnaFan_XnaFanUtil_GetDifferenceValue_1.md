# XnaFanUtil.GetDifferenceValue Method (String, String, Int32)
 

Gets a value indicating the percentage of difference between two images.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float GetDifferenceValue(
	string imageFilepath1,
	string imageFilepath2,
	int threshold = 1
)
```

**VB**<br />
``` VB
Public Shared Function GetDifferenceValue ( 
	imageFilepath1 As String,
	imageFilepath2 As String,
	Optional threshold As Integer = 1
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim imageFilepath1 As String
Dim imageFilepath2 As String
Dim threshold As Integer
Dim returnValue As Single

returnValue = XnaFanUtil.GetDifferenceValue(imageFilepath1, 
	imageFilepath2, threshold)
```

**C++**<br />
``` C++
public:
static float GetDifferenceValue(
	String^ imageFilepath1, 
	String^ imageFilepath2, 
	int threshold = 1
)
```

**F#**<br />
``` F#
static member GetDifferenceValue : 
        imageFilepath1 : string * 
        imageFilepath2 : string * 
        ?threshold : int 
(* Defaults:
        let _threshold = defaultArg threshold 1
*)
-> float32 

```


#### Parameters
&nbsp;<dl><dt>imageFilepath1</dt><dd>Type: System.String<br />The filepath of the first image to compare.</dd><dt>imageFilepath2</dt><dd>Type: System.String<br />The filepath of the second image to compare.</dd><dt>threshold (Optional)</dt><dd>Type: System.Int32<br />A value, from `0` to `100`, indicating how big a difference will be ignored. 

 Default value is `1`.</dd></dl>

#### Return Value
Type: Single<br />The resulting percentage value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img1 As Image = "C:\Image1.jpg"
Dim img2 As Image = "C:\Image2.jpg"
Dim threshold As Integer = 1

Dim percentDiff As String =
    String.Format("Percentage Difference: {0:0.00}%",
                  GetDifferenceValue(img1, img2, threshold))

MessageBox.Show(percentDiff)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_XnaFan_XnaFanUtil">XnaFanUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_XnaFan_XnaFanUtil_GetDifferenceValue">GetDifferenceValue Overload</a><br /><a href="N_DevCase_ThirdParty_XnaFan">DevCase.ThirdParty.XnaFan Namespace</a><br />