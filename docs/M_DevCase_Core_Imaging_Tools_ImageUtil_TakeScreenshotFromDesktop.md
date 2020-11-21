# ImageUtil.TakeScreenshotFromDesktop Method 
 

Takes a screenshot of the desktop.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image TakeScreenshotFromDesktop(
	bool includeTaskBar,
	bool includeMouse,
	PixelFormat pixelFormat = PixelFormat.Format32bppArgb
)
```

**VB**<br />
``` VB
Public Shared Function TakeScreenshotFromDesktop ( 
	includeTaskBar As Boolean,
	includeMouse As Boolean,
	Optional pixelFormat As PixelFormat = PixelFormat.Format32bppArgb
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim includeTaskBar As Boolean
Dim includeMouse As Boolean
Dim pixelFormat As PixelFormat
Dim returnValue As Image

returnValue = ImageUtil.TakeScreenshotFromDesktop(includeTaskBar, 
	includeMouse, pixelFormat)
```

**C++**<br />
``` C++
public:
static Image^ TakeScreenshotFromDesktop(
	bool includeTaskBar, 
	bool includeMouse, 
	PixelFormat pixelFormat = PixelFormat::Format32bppArgb
)
```

**F#**<br />
``` F#
static member TakeScreenshotFromDesktop : 
        includeTaskBar : bool * 
        includeMouse : bool * 
        ?pixelFormat : PixelFormat 
(* Defaults:
        let _pixelFormat = defaultArg pixelFormat PixelFormat.Format32bppArgb
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>includeTaskBar</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the Taskbar is drawn in the resulting image.</dd><dt>includeMouse</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the mouse is drawn in the resulting image.</dd><dt>pixelFormat (Optional)</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The image pixel format.</dd></dl>

#### Return Value
Type: Image<br />The resulting image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim jpgCodec As ImageCodecInfo =
    (From codec As ImageCodecInfo In ImageCodecInfo.GetImageDecoders
     Where codec.FormatID = ImageFormat.Jpeg.Guid).SingleOrDefault

Dim encoderParams As New EncoderParameters(1)
Dim qualityEncoder As Imaging.Encoder = Imaging.Encoder.Quality
Dim qualityParameter As New EncoderParameter(qualityEncoder, 80)
encoderParams.Param(0) = qualityParameter

Dim screenshot As Image = TakeScreenshotFromDesktop(includeTaskBar:=False, includeMouse:=False)
screenShot.Save("C:\Screenshot.jpg", jpgCodec, encoderParams)
Process.Start("C:\Screenshot.jpg")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />