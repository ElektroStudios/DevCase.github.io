# DrawingUtil.GetRandomSizeF Method (Single, Single)
 

Gets a random SizeF between the specified maximum width and height.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SizeF GetRandomSizeF(
	float wMax,
	float hMax
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomSizeF ( 
	wMax As Single,
	hMax As Single
) As SizeF
```

**VB Usage**<br />
``` VB Usage
Dim wMax As Single
Dim hMax As Single
Dim returnValue As SizeF

returnValue = DrawingUtil.GetRandomSizeF(wMax, 
	hMax)
```

**C++**<br />
``` C++
public:
static SizeF GetRandomSizeF(
	float wMax, 
	float hMax
)
```

**F#**<br />
``` F#
static member GetRandomSizeF : 
        wMax : float32 * 
        hMax : float32 -> SizeF 

```


#### Parameters
&nbsp;<dl><dt>wMax</dt><dd>Type: System.Single<br />The maximum width.</dd><dt>hMax</dt><dd>Type: System.Single<br />The maximum height.</dd></dl>

#### Return Value
Type: SizeF<br />The resulting SizeF.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_DrawingUtil_GetRandomSizeF">GetRandomSizeF Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />