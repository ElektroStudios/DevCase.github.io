# IconProUtil.CreateIconBitmapEncoder Method (Bitmap, Int32[])
 

Creates a IconBitmapEncoder from the specified Image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IconBitmapEncoder CreateIconBitmapEncoder(
	Bitmap bmp,
	params int[] squareSizes
)
```

**VB**<br />
``` VB
Public Shared Function CreateIconBitmapEncoder ( 
	bmp As Bitmap,
	ParamArray squareSizes As Integer()
) As IconBitmapEncoder
```

**VB Usage**<br />
``` VB Usage
Dim bmp As Bitmap
Dim squareSizes As Integer()
Dim returnValue As IconBitmapEncoder

returnValue = IconProUtil.CreateIconBitmapEncoder(bmp, 
	squareSizes)
```

**C++**<br />
``` C++
public:
static IconBitmapEncoder^ CreateIconBitmapEncoder(
	Bitmap^ bmp, 
	... array<int>^ squareSizes
)
```

**F#**<br />
``` F#
static member CreateIconBitmapEncoder : 
        bmp : Bitmap * 
        squareSizes : int[] -> IconBitmapEncoder 

```


#### Parameters
&nbsp;<dl><dt>bmp</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd><dt>squareSizes</dt><dd>Type: System.Int32[]<br />The square sizes to include in the icon (eg. 16 = 16x16, 32 = 32x32, etc). 

 If no value is specified, the size of the source image specified at *bmp* will be used.</dd></dl>

#### Return Value
Type: IconBitmapEncoder<br />The resulting IconBitmapEncoder.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim imgPath As String = "C:\Image.png"
Dim bmp As Bitmap = DirectCast(Bitmap.FromFile(imgPath), Bitmap)
Dim enc As IconBitmapEncoder = CreateIconBitmapEncoder(bmp, 16, 24, 32, 48, 64, 96, 128, 256)

Using output As New FileStream("C:\New Icon.ico", FileMode.CreateNew, FileAccess.Write, FileShare.Read)
    enc.Save(output)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_IconPro_IconProUtil">IconProUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_IconPro_IconProUtil_CreateIconBitmapEncoder">CreateIconBitmapEncoder Overload</a><br /><a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro Namespace</a><br />