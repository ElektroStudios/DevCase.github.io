# FreeImageUtil.GrayScale Method (String)
 

Grayscales the specified image file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap GrayScale(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GrayScale ( 
	filepath As String
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Bitmap

returnValue = FreeImageUtil.GrayScale(filepath)
```

**C++**<br />
``` C++
public:
static Bitmap^ GrayScale(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GrayScale : 
        filepath : string -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source image filepath.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_GrayScale">GrayScale Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />