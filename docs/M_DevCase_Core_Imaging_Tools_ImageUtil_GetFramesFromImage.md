# ImageUtil.GetFramesFromImage Method 
 

Gets a List(T) containing all the frames in the source GIF image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<Bitmap> GetFramesFromImage(
	Image img
)
```

**VB**<br />
``` VB
Public Shared Function GetFramesFromImage ( 
	img As Image
) As List(Of Bitmap)
```

**VB Usage**<br />
``` VB Usage
Dim img As Image
Dim returnValue As List(Of Bitmap)

returnValue = ImageUtil.GetFramesFromImage(img)
```

**C++**<br />
``` C++
public:
static List<Bitmap^>^ GetFramesFromImage(
	Image^ img
)
```

**F#**<br />
``` F#
static member GetFramesFromImage : 
        img : Image -> List<Bitmap> 

```


#### Parameters
&nbsp;<dl><dt>img</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd></dl>

#### Return Value
Type: List(Bitmap)<br />The resulting percentage difference value between the two specified images.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ImageUtil">ImageUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />