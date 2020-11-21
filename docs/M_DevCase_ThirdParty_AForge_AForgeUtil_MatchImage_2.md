# AForgeUtil.MatchImage Method (IntPtr, Bitmap, Single)
 

Matches a part of an image in the specified window, and returns the relative top-left corner coordinates of any matched image and their similarity percent.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AForge">DevCase.ThirdParty.AForge</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TemplateMatch[] MatchImage(
	IntPtr hWnd,
	Bitmap findImage,
	float similarity
)
```

**VB**<br />
``` VB
Public Shared Function MatchImage ( 
	hWnd As IntPtr,
	findImage As Bitmap,
	similarity As Single
) As TemplateMatch()
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim findImage As Bitmap
Dim similarity As Single
Dim returnValue As TemplateMatch()

returnValue = AForgeUtil.MatchImage(hWnd, 
	findImage, similarity)
```

**C++**<br />
``` C++
public:
static array<TemplateMatch^>^ MatchImage(
	IntPtr hWnd, 
	Bitmap^ findImage, 
	float similarity
)
```

**F#**<br />
``` F#
static member MatchImage : 
        hWnd : IntPtr * 
        findImage : Bitmap * 
        similarity : float32 -> TemplateMatch[] 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the source window.</dd><dt>findImage</dt><dd>Type: System.Drawing.Bitmap<br />The image to find.</dd><dt>similarity</dt><dd>Type: System.Single<br />The similarity percentage threshold to compare the image. 

 A value of `100` means find a 100% identical image. 

 Note: High percentage values with images of big resolutions could take several minutes to accomplish.</dd></dl>

#### Return Value
Type: TemplateMatch[]<br />An Array of TemplateMatch that contains the relative top-left corner coordinates of any matched image and their similarity percent.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd As IntPtr = Process.GetCurrentProcess().MainWindowHandle
Dim findImage As New Bitmap("C:\Image.png")
Dim matches As TemplateMatch() = MatchImage(hWnd, findImage, 80.5F) ' 80,5% similarity threeshold.

For Each match As TemplateMatch In matches
    Dim sb As New StringBuilder()
    sb.AppendFormat("Client Coordinates: {0}", match.Rectangle.Location.ToString())
    sb.AppendFormat("Screen Coordinates: {0}", DevCase.ThirdParty.AForge.Extensions.TemplateMatch.ToScreenCoordinates(match, hWnd).Location.ToString())
    sb.AppendFormat("Similarity Image Percentage: {0}%", (match.Similarity * 100.0F).ToString("00.00"))
    sb.AppendLine()
    Console.WriteLine(sb.ToString())
Next match
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AForge_AForgeUtil">AForgeUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_AForge_AForgeUtil_MatchImage">MatchImage Overload</a><br /><a href="N_DevCase_ThirdParty_AForge">DevCase.ThirdParty.AForge Namespace</a><br />