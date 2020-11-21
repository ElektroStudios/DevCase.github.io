# ImageUtil.TakeScreenshotFromRegion Method (Point, Size, Boolean, PixelFormat)
 

Takes a screenshot of a screen region.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image TakeScreenshotFromRegion(
	Point location,
	Size size,
	bool includeMouse,
	PixelFormat pixelFormat = PixelFormat.Format32bppArgb
)
```

**VB**<br />
``` VB
Public Shared Function TakeScreenshotFromRegion ( 
	location As Point,
	size As Size,
	includeMouse As Boolean,
	Optional pixelFormat As PixelFormat = PixelFormat.Format32bppArgb
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim location As Point
Dim size As Size
Dim includeMouse As Boolean
Dim pixelFormat As PixelFormat
Dim returnValue As Image

returnValue = ImageUtil.TakeScreenshotFromRegion(location, 
	size, includeMouse, pixelFormat)
```

**C++**<br />
``` C++
public:
static Image^ TakeScreenshotFromRegion(
	Point location, 
	Size size, 
	bool includeMouse, 
	PixelFormat pixelFormat = PixelFormat::Format32bppArgb
)
```

**F#**<br />
``` F#
static member TakeScreenshotFromRegion : 
        location : Point * 
        size : Size * 
        includeMouse : bool * 
        ?pixelFormat : PixelFormat 
(* Defaults:
        let _pixelFormat = defaultArg pixelFormat PixelFormat.Format32bppArgb
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>location</dt><dd>Type: System.Drawing.Point<br />The X-coordinate is the point at the upper-left corner of the region. The Y-coordinate is the point at the upper-left corner of the region.</dd><dt>size</dt><dd>Type: System.Drawing.Size<br />The size of the area to be transferred.</dd><dt>includeMouse</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the mouse is drawn in the resulting image.</dd><dt>pixelFormat (Optional)</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The image pixel format.</dd></dl>

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

Dim screenshot As Image = TakeScreenshotFromRegion(New Point(0, 0), New Size(256, 256), includeMouse:=True)
screenShot.Save("C:\Screenshot.jpg", jpgCodec, encoderParams)
Process.Start("C:\Screenshot.jpg")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ImageUtil_TakeScreenshotFromRegion">TakeScreenshotFromRegion Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />