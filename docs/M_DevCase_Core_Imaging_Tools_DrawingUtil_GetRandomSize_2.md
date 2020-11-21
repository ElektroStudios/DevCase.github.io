# DrawingUtil.GetRandomSize Method (Int32, Int32)
 

Gets a random Size between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Size GetRandomSize(
	int wMax,
	int hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomSize ( 
	wMax As Integer,
	hMax As Integer
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim wMax As Integer
Dim hMax As Integer
Dim returnValue As Size

returnValue = DrawingUtil.GetRandomSize(wMax, 
	hMax)
```

**C++**<br />
``` C++
public:
static Size GetRandomSize(
	int wMax, 
	int hMax
)
```

**F#**<br />
``` F#
static member GetRandomSize : 
        wMax : int * 
        hMax : int -> Size 

```


#### Parameters
&nbsp;<dl><dt>wMax</dt><dd>Type: System.Int32<br />The maximum width.</dd><dt>hMax</dt><dd>Type: System.Int32<br />The maximum height.</dd></dl>

#### Return Value
Type: Size<br />The resulting Size.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomSize">GetRandomSize Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />