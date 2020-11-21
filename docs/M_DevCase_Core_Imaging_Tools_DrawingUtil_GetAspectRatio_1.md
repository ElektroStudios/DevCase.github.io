# DrawingUtil.GetAspectRatio Method (Int32, Int32)
 

Determine the aspect ratio of the source resolution.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point GetAspectRatio(
	int width,
	int height
)
```

**VB**<br />
``` VB
Public Shared Function GetAspectRatio ( 
	width As Integer,
	height As Integer
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim width As Integer
Dim height As Integer
Dim returnValue As Point

returnValue = DrawingUtil.GetAspectRatio(width, 
	height)
```

**C++**<br />
``` C++
public:
static Point GetAspectRatio(
	int width, 
	int height
)
```

**F#**<br />
``` F#
static member GetAspectRatio : 
        width : int * 
        height : int -> Point 

```


#### Parameters
&nbsp;<dl><dt>width</dt><dd>Type: System.Int32<br />The resolution width.</dd><dt>height</dt><dd>Type: System.Int32<br />The resolution height.</dd></dl>

#### Return Value
Type: Point<br />The resulting aspect ratio, expressed as X:Y.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim width As Integer = 1920
Dim height As Integer = 1080
Dim aspectRatio As Point = GetAspectRatio(width, height)

Console.WriteLine(aspectRatio.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetAspectRatio">GetAspectRatio Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />