# IconProUtil.CreateIcon Method (Image, Boolean, Int32[])
 

Creates a icon from the specified Image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MemoryStream CreateIcon(
	Image img,
	bool usePngCompression,
	params int[] squareSizes
)
```

**VB**<br />
``` VB
Public Shared Function CreateIcon ( 
	img As Image,
	usePngCompression As Boolean,
	ParamArray squareSizes As Integer()
) As MemoryStream
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim usePngCompression As Boolean
Dim squareSizes As Integer()
Dim returnValue As MemoryStream

returnValue = IconProUtil.CreateIcon(img, 
	usePngCompression, squareSizes)
```

**C++**<br />
``` C++
public:
static MemoryStream^ CreateIcon(
	Image^ img, 
	bool usePngCompression, 
	... array<int>^ squareSizes
)
```

**F#**<br />
``` F#
static member CreateIcon : 
        img : Image * 
        usePngCompression : bool * 
        squareSizes : int[] -> MemoryStream 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd><dt>usePngCompression</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), use PNG compression.</dd><dt>squareSizes</dt><dd>Type: System.Int32[]<br />The square sizes to include in the icon (eg. 16 = 16x16, 32 = 32x32, etc). 

 If no value is specified, the size of the source image specified at *img* will be used.</dd></dl>

#### Return Value
Type: MemoryStream<br />A MemoryStream that contains the raw icon data. Save the stream to disk to create a icon file.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim imgPath As String = "C:\Image.png"
Dim img As Image = Image.FromFile(imgPath)

Using iconStream As MemoryStream = CreateIcon(img, True, 16, 24, 32, 48, 64, 96, 128, 256),
      output As New FileStream("C:\New Icon.ico", FileMode.CreateNew, FileAccess.Write, FileShare.Read)

    iconStream.WriteTo(output)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_IconPro_IconProUtil">IconProUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_IconPro_IconProUtil_CreateIcon">CreateIcon Overload</a><br /><a href="N_DevCase_ThirdParty_IconPro">DevCase.ThirdParty.IconPro Namespace</a><br />