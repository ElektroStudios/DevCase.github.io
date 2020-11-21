# DrawingUtil.GetRandomRectangle Method (Size)
 

Gets a random Rectangle with a size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Rectangle GetRandomRectangle(
	Size sizeMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomRectangle ( 
	sizeMax As Size
) As Rectangle
```

**VB Usage**<br />
``` VB Usage
Dim sizeMax As Size
Dim returnValue As Rectangle

returnValue = DrawingUtil.GetRandomRectangle(sizeMax)
```

**C++**<br />
``` C++
public:
static Rectangle GetRandomRectangle(
	Size sizeMax
)
```

**F#**<br />
``` F#
static member GetRandomRectangle : 
        sizeMax : Size -> Rectangle 

```


#### Parameters
&nbsp;<dl><dt>sizeMax</dt><dd>Type: System.Drawing.Size<br />A Size that specifies the maximum width and height.</dd></dl>

#### Return Value
Type: Rectangle<br />The resulting Rectangle.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomRectangle">GetRandomRectangle Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />