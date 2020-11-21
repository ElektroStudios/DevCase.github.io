# DrawingUtil.GetAspectRatio Method (Size)
 

Determine the aspect ratio of the source resolution.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point GetAspectRatio(
	Size resolution
)
```

**VB**<br />
``` VB
Public Shared Function GetAspectRatio ( 
	resolution As Size
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim resolution As Size
Dim returnValue As Point

returnValue = DrawingUtil.GetAspectRatio(resolution)
```

**C++**<br />
``` C++
public:
static Point GetAspectRatio(
	Size resolution
)
```

**F#**<br />
``` F#
static member GetAspectRatio : 
        resolution : Size -> Point 

```


#### Parameters
&nbsp;<dl><dt>resolution</dt><dd>Type: System.Drawing.Size<br />The source resolution.</dd></dl>

#### Return Value
Type: Point<br />The resulting aspect ratio, expressed as X:Y.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim resolution As New Size(width:=1920, height:=1080)
Dim aspectRatio As Point = GetAspectRatio(resolution)

Console.WriteLine(aspectRatio.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetAspectRatio">GetAspectRatio Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />