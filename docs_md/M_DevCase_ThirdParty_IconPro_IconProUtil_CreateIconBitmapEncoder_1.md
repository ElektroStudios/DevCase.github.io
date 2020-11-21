# IconProUtil.CreateIconBitmapEncoder Method (Image, Int32[])
 

Creates a IconBitmapEncoder from the specified Image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IconBitmapEncoder CreateIconBitmapEncoder(
	Image img,
	params int[] squareSizes
)
```

**VB**<br />
``` VB
Public Shared Function CreateIconBitmapEncoder ( 
	img As Image,
	ParamArray squareSizes As Integer()
) As IconBitmapEncoder
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim squareSizes As Integer()
Dim returnValue As IconBitmapEncoder

returnValue = IconProUtil.CreateIconBitmapEncoder(img, 
	squareSizes)
```

**C++**<br />
``` C++
public:
static IconBitmapEncoder^ CreateIconBitmapEncoder(
	Image^ img, 
	... array<int>^ squareSizes
)
```

**F#**<br />
``` F#
static member CreateIconBitmapEncoder : 
        img : Image * 
        squareSizes : int[] -> IconBitmapEncoder 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>squareSizes</dt><dd>Type: System.Int32[]<br />The square sizes to include in the icon (eg. 16 = 16x16, 32 = 32x32, etc). 

 If no value is specified, the size of the source image specified at *img* will be used.</dd></dl>

#### Return Value
Type: IconBitmapEncoder<br />The resulting IconBitmapEncoder.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim imgPath As String = "C:\Image.png"
Dim img As Image = Image.FromFile(imgPath)
Dim enc As IconBitmapEncoder = CreateIconBitmapEncoder(img, 16, 24, 32, 48, 64, 96, 128, 256)

Using output As New FileStream("C:\New Icon.ico", FileMode.CreateNew, FileAccess.Write, FileShare.Read)
    enc.Save(output)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_IconPro_IconProUtil">IconProUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_IconPro_IconProUtil_CreateIconBitmapEncoder">CreateIconBitmapEncoder Overload</a><br /><a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro Namespace</a><br />