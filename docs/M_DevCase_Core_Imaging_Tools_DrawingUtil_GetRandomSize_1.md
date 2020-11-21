# DrawingUtil.GetRandomSize Method (Size)
 

Gets a random Size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Size GetRandomSize(
	Size sizeMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomSize ( 
	sizeMax As Size
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim sizeMax As Size
Dim returnValue As Size

returnValue = DrawingUtil.GetRandomSize(sizeMax)
```

**C++**<br />
``` C++
public:
static Size GetRandomSize(
	Size sizeMax
)
```

**F#**<br />
``` F#
static member GetRandomSize : 
        sizeMax : Size -> Size 

```


#### Parameters
&nbsp;<dl><dt>sizeMax</dt><dd>Type: System.Drawing.Size<br />A Size that specifies the maximum width and height.</dd></dl>

#### Return Value
Type: Size<br />The resulting Size.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomSize">GetRandomSize Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />