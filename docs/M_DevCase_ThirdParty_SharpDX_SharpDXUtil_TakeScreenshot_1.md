# SharpDXUtil.TakeScreenshot Method (Int32, Boolean)
 

Captures the screen output using the specified graphics card adapter. 

 This DirectX based methodology is useful to take screenshot of games that are running in full screen. 

 However, using this methodology for other common desktop screen captures will produce unexpected results (such as wrong colors); so for common screenshots you should use the methods exposed in <a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil</a> instead.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image TakeScreenshot(
	int adapterIndex,
	bool includeMouse
)
```

**VB**<br />
``` VB
Public Shared Function TakeScreenshot ( 
	adapterIndex As Integer,
	includeMouse As Boolean
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim adapterIndex As Integer
Dim includeMouse As Boolean
Dim returnValue As Image

returnValue = SharpDXUtil.TakeScreenshot(adapterIndex, 
	includeMouse)
```

**C++**<br />
``` C++
public:
static Image^ TakeScreenshot(
	int adapterIndex, 
	bool includeMouse
)
```

**F#**<br />
``` F#
static member TakeScreenshot : 
        adapterIndex : int * 
        includeMouse : bool -> Image 

```


#### Parameters
&nbsp;<dl><dt>adapterIndex</dt><dd>Type: System.Int32<br />The index of the graphics card adapter. 

 Set this value to `0` if you don't have more than one graphics card.</dd><dt>includeMouse</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the mouse is drawn in the resulting image.</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

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

Dim screenshot As Image = TakeScreenshot(adapterIndex:=0, includeMouse:=True)
screenShot.Save("C:\Screenshot.jpg", jpgCodec, encoderParams)
Process.Start("C:\Screenshot.jpg")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SharpDX_SharpDXUtil">SharpDXUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_SharpDX_SharpDXUtil_TakeScreenshot">TakeScreenshot Overload</a><br /><a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />