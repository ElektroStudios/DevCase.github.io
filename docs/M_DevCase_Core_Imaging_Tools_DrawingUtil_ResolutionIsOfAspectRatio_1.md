# DrawingUtil.ResolutionIsOfAspectRatio Method (Int32, Int32, Point)
 

Determine whether the source resolution belongs to the specified aspect ratio.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ResolutionIsOfAspectRatio(
	int width,
	int height,
	Point aspectRatio
)
```

**VB**<br />
``` VB
Public Shared Function ResolutionIsOfAspectRatio ( 
	width As Integer,
	height As Integer,
	aspectRatio As Point
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim width As Integer
Dim height As Integer
Dim aspectRatio As Point
Dim returnValue As Boolean

returnValue = DrawingUtil.ResolutionIsOfAspectRatio(width, 
	height, aspectRatio)
```

**C++**<br />
``` C++
public:
static bool ResolutionIsOfAspectRatio(
	int width, 
	int height, 
	Point aspectRatio
)
```

**F#**<br />
``` F#
static member ResolutionIsOfAspectRatio : 
        width : int * 
        height : int * 
        aspectRatio : Point -> bool 

```


#### Parameters
&nbsp;<dl><dt>width</dt><dd>Type: System.Int32<br />The resolution width.</dd><dt>height</dt><dd>Type: System.Int32<br />The resolution height.</dd><dt>aspectRatio</dt><dd>Type: System.Drawing.Point<br />The aspect ratio.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the source resolution belongs to the specified aspect ratio; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim width As Integer = 1920
Dim height As Integer = 1080
Dim aspectRatio As New Point(x:=16, y:=9)

Dim result As Boolean = ResolutionIsOfAspectRatio(width, height, aspectRatio)

Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_ResolutionIsOfAspectRatio">ResolutionIsOfAspectRatio Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />