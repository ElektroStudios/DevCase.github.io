# AForgeUtil.MatchImage Method (String, String, Single)
 

Matches a part of an image inside of the specified source image, and returns the relative top-left corner coordinates of any matched image and their similarity percent.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_AForge">DevCase.ThirdParty.AForge</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TemplateMatch[] MatchImage(
	string srcImagePath,
	string findImagePath,
	float similarity
)
```

**VB**<br />
``` VB
Public Shared Function MatchImage ( 
	srcImagePath As String,
	findImagePath As String,
	similarity As Single
) As TemplateMatch()
```

**VB Usage**<br />
``` VB Usage
Dim srcImagePath As String
Dim findImagePath As String
Dim similarity As Single
Dim returnValue As TemplateMatch()

returnValue = AForgeUtil.MatchImage(srcImagePath, 
	findImagePath, similarity)
```

**C++**<br />
``` C++
public:
static array<TemplateMatch^>^ MatchImage(
	String^ srcImagePath, 
	String^ findImagePath, 
	float similarity
)
```

**F#**<br />
``` F#
static member MatchImage : 
        srcImagePath : string * 
        findImagePath : string * 
        similarity : float32 -> TemplateMatch[] 

```


#### Parameters
&nbsp;<dl><dt>srcImagePath</dt><dd>Type: System.String<br />The filepath of the source image.</dd><dt>findImagePath</dt><dd>Type: System.String<br />The filepath of the image to find inside *srcImagePath* image.</dd><dt>similarity</dt><dd>Type: System.Single<br />The similarity percentage threshold to compare the images. 

 A value of `100` means find a 100% identical image. 

 Note: High percentage values with images of big resolutions could take several minutes to accomplish.</dd></dl>

#### Return Value
Type: TemplateMatch[]<br />An Array of TemplateMatch that contains the relative top-left corner coordinates of any matched image and their similarity percent.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>similarity</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
' A desktop screenshot, in 1920x1080 px. resolution.
Dim desktopScreenshot As String = "C:\Desktop.png"

' A cutted piece of the screenshot, in 50x50 px. resolution.
Dim partOfDesktopToFind As String = "C:\PieceOfDesktop.png"

' Match part of the image in the desktop, with the specified similarity threeshold.
Dim matches As TemplateMatch() = MatchImage(srcImagePath:=desktopScreenshot,
                                            findImagePath:=partOfDesktopToFind,
                                            similarity:=80.5F) ' 80,5% similarity threeshold.

For Each match As TemplateMatch In matches

    Dim sb As New System.Text.StringBuilder
    sb.AppendFormat("Top-Left Corner Coordinates: {0}", match.Rectangle.Location.ToString())
    sb.AppendLine()
    sb.AppendFormat("Similarity Image Percentage: {0}%", (match.Similarity * 100.0F).ToString("00.00"))

    MessageBox.Show(sb.ToString())

Next match
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_AForge_AForgeUtil">AForgeUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_AForge_AForgeUtil_MatchImage">MatchImage Overload</a><br /><a href="N_DevCase_ThirdParty_AForge">DevCase.ThirdParty.AForge Namespace</a><br />