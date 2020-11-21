# DrawingUtil.GetRandomSize Method (Int32, Int32, Int32, Int32)
 

Gets a random Size between the specified minimum and maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Size GetRandomSize(
	int wMin,
	int wMax,
	int hMin,
	int hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomSize ( 
	wMin As Integer,
	wMax As Integer,
	hMin As Integer,
	hMax As Integer
) As Size
```

**VB Usage**<br />
``` VB Usage
Dim wMin As Integer
Dim wMax As Integer
Dim hMin As Integer
Dim hMax As Integer
Dim returnValue As Size

returnValue = DrawingUtil.GetRandomSize(wMin, 
	wMax, hMin, hMax)
```

**C++**<br />
``` C++
public:
static Size GetRandomSize(
	int wMin, 
	int wMax, 
	int hMin, 
	int hMax
)
```

**F#**<br />
``` F#
static member GetRandomSize : 
        wMin : int * 
        wMax : int * 
        hMin : int * 
        hMax : int -> Size 

```


#### Parameters
&nbsp;<dl><dt>wMin</dt><dd>Type: System.Int32<br />The minimum width.</dd><dt>wMax</dt><dd>Type: System.Int32<br />The maximum width.</dd><dt>hMin</dt><dd>Type: System.Int32<br />The minimum height.</dd><dt>hMax</dt><dd>Type: System.Int32<br />The maximum height.</dd></dl>

#### Return Value
Type: Size<br />The resulting Size.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomSize">GetRandomSize Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />