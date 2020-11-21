# ImageUtil.TakeScreenshotFromObject Method 
 

Takes a screenshot of an object in the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image TakeScreenshotFromObject(
	IntPtr hWnd,
	bool includeMouse,
	PixelFormat pixelFormat = PixelFormat.Format32bppArgb
)
```

**VB**<br />
``` VB
Public Shared Function TakeScreenshotFromObject ( 
	hWnd As IntPtr,
	includeMouse As Boolean,
	Optional pixelFormat As PixelFormat = PixelFormat.Format32bppArgb
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim includeMouse As Boolean
Dim pixelFormat As PixelFormat
Dim returnValue As Image

returnValue = ImageUtil.TakeScreenshotFromObject(hWnd, 
	includeMouse, pixelFormat)
```

**C++**<br />
``` C++
public:
static Image^ TakeScreenshotFromObject(
	IntPtr hWnd, 
	bool includeMouse, 
	PixelFormat pixelFormat = PixelFormat::Format32bppArgb
)
```

**F#**<br />
``` F#
static member TakeScreenshotFromObject : 
        hWnd : IntPtr * 
        includeMouse : bool * 
        ?pixelFormat : PixelFormat 
(* Defaults:
        let _pixelFormat = defaultArg pixelFormat PixelFormat.Format32bppArgb
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The IntPtr window handle to the object.</dd><dt>includeMouse</dt><dd>Type: System.Boolean<br />\[Missing <param name="includeMouse"/> documentation for "M:DevCase.Core.Imaging.Tools.ImageUtil.TakeScreenshotFromObject(System.IntPtr,System.Boolean,System.Drawing.Imaging.PixelFormat)"\]</dd><dt>pixelFormat (Optional)</dt><dd>Type: System.Drawing.Imaging.PixelFormat<br />The image pixel format.</dd></dl>

#### Return Value
Type: Image<br />The resulting image.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified handle is not a valid window handle (hWnd).</td></tr><tr><td>ArgumentException</td><td>The specified window is hidden.</td></tr><tr><td>Win32Exception</td><td /></tr></table>

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

Dim hwnd As IntPtr = Process.GetProcessesByName("notepad").FirstOrDefault.MainWindowHandle

Dim screenshot As Image = TakeScreenshotFromObject(hwnd, includeMouse:=True)
screenShot.Save("C:\Screenshot.jpg", jpgCodec, encoderParams)
Process.Start("C:\Screenshot.jpg")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />