# ImageUtil.OverlayImages Method 
 

Overlay a Image over another Image used as background.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image OverlayImages(
	Image backImage,
	Image topImage,
	int topPosX = 0,
	int topPosY = 0
)
```

**VB**<br />
``` VB
Public Shared Function OverlayImages ( 
	backImage As Image,
	topImage As Image,
	Optional topPosX As Integer = 0,
	Optional topPosY As Integer = 0
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim backImage As Image
Dim topImage As Image
Dim topPosX As Integer
Dim topPosY As Integer
Dim returnValue As Image

returnValue = ImageUtil.OverlayImages(backImage, 
	topImage, topPosX, topPosY)
```

**C++**<br />
``` C++
public:
static Image^ OverlayImages(
	Image^ backImage, 
	Image^ topImage, 
	int topPosX = 0, 
	int topPosY = 0
)
```

**F#**<br />
``` F#
static member OverlayImages : 
        backImage : Image * 
        topImage : Image * 
        ?topPosX : int * 
        ?topPosY : int 
(* Defaults:
        let _topPosX = defaultArg topPosX 0
        let _topPosY = defaultArg topPosY 0
*)
-> Image 

```


#### Parameters
&nbsp;<dl><dt>backImage</dt><dd>Type: System.Drawing.Image<br />The background Image.</dd><dt>topImage</dt><dd>Type: System.Drawing.Image<br />The topmost Image.</dd><dt>topPosX (Optional)</dt><dd>Type: System.Int32<br />An adjustment of the "X" position of the topmost Image.</dd><dt>topPosY (Optional)</dt><dd>Type: System.Int32<br />An adjustment of the "Y" position of the topmost Image.</dd></dl>

#### Return Value
Type: Image<br />The overlayed image.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>backImage or topImage</td></tr><tr><td>ArgumentException</td><td>Image bounds are greater than background image.;topImage</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim backImg As Image = Image.FromFile("C:\back.jpg")
Dim topImg As Image = Image.FromFile("C:\top.png")
Dim overlay As Image = OverlayImages(backImg, topImg, topPosX:=+5, topPosY:=-15)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />