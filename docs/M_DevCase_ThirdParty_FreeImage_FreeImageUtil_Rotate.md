# FreeImageUtil.Rotate Method (Bitmap, Double)
 

Rotates the specified image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Bitmap Rotate(
	Bitmap bmp,
	double angle
)
```

**VB**<br />
``` VB
Public Shared Function Rotate ( 
	bmp As Bitmap,
	angle As Double
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim angle As Double
Dim returnValue As Bitmap

returnValue = FreeImageUtil.Rotate(bmp, angle)
```

**C++**<br />
``` C++
public:
static Bitmap^ Rotate(
	Bitmap^ bmp, 
	double angle
)
```

**F#**<br />
``` F#
static member Rotate : 
        bmp : Bitmap * 
        angle : float -> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>angle</dt><dd>Type: System.Double<br />The rotation angle.</dd></dl>

#### Return Value
Type: Bitmap<br />The resulting image.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_FreeImage_FreeImageUtil_Rotate">Rotate Overload</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />