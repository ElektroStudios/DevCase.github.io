# AsposeUtil.AddTextWatermark Method (Image, String, Font, Color, WatermarkPosition, Single, Single)
 

Adds a text watermark at a prefedined position into an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Aspose">DevCase.ThirdParty.Aspose</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image AddTextWatermark(
	Image img,
	string text,
	Font fnt,
	Color color,
	WatermarkPosition position,
	float verticalmargin = 0f,
	float horizontalmargin = 0f
)
```

**VB**<br />
``` VB
Public Shared Function AddTextWatermark ( 
	img As Image,
	text As String,
	fnt As Font,
	color As Color,
	position As WatermarkPosition,
	Optional verticalmargin As Single = 0F,
	Optional horizontalmargin As Single = 0F
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim text As String
Dim fnt As Font
Dim color As Color
Dim position As WatermarkPosition
Dim verticalmargin As Single
Dim horizontalmargin As Single
Dim returnValue As Image

returnValue = AsposeUtil.AddTextWatermark(img, 
	text, fnt, color, position, verticalmargin, 
	horizontalmargin)
```

**C++**<br />
``` C++
public:
static Image^ AddTextWatermark(
	Image^ img, 
	String^ text, 
	Font^ fnt, 
	Color color, 
	WatermarkPosition position, 
	float verticalmargin = 0f, 
	float horizontalmargin = 0f
)
```

**F#**<br />
``` F#
static member AddTextWatermark : 
        img : Image * 
        text : string * 
        fnt : Font * 
        color : Color * 
        position : WatermarkPosition * 
        ?verticalmargin : float32 * 
        ?horizontalmargin : float32 
(* Defaults:
        let _verticalmargin = defaultArg verticalmargin 0f
        let _horizontalmargin = defaultArg horizontalmargin 0f
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: Image<br />The source image.</dd><dt>text</dt><dd>Type: System.String<br />The watermark text.</dd><dt>fnt</dt><dd>Type: Font<br />The watermark font.</dd><dt>color</dt><dd>Type: Color<br />The watermark color.</dd><dt>position</dt><dd>Type: <a href="T_DevCase_ThirdParty_Aspose_WatermarkPosition">DevCase.ThirdParty.Aspose.WatermarkPosition</a><br />The watermark position.</dd><dt>verticalmargin (Optional)</dt><dd>Type: System.Single<br />The watermark vertical margin.</dd><dt>horizontalmargin (Optional)</dt><dd>Type: System.Single<br />The watermark horizontal margin.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Load an image to add a watermark.
Dim img As Aspose.Imaging.Image = Aspose.Imaging.Image.Load("C:\image.bmp")

' Set the watermark text.
Dim text As String = "ElektroStudios"

' Set the watermark text color.
Dim color As Global.Aspose.Imaging.Color = Aspose.Imaging.Color.White

' Set the watermark text font.
Dim fnt As New Aspose.Imaging.Font("Lucida Console", 32, FontStyle.Bold)

' Add the watermark into the image.
img = AddTextWatermark(img:=img, text:=text, fnt:=fnt, color:=color, position:=WatermarkPosition.BottomRight)

' Save the image to disk.
img.Save("C:\Watermark.bmp")

' See the resulting image.
Process.Start("C:\Watermark.bmp")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Aspose_AsposeUtil">AsposeUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_Aspose_AsposeUtil_AddTextWatermark">AddTextWatermark Overload</a><br /><a href="N_DevCase_ThirdParty_Aspose">DevCase.ThirdParty.Aspose Namespace</a><br />