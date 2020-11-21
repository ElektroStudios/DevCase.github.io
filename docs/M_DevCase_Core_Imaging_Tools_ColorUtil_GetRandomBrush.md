# ColorUtil.GetRandomBrush Method (Boolean)
 

Generates a random SolidBrush.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SolidBrush GetRandomBrush(
	bool includeAlphaChannel = false
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomBrush ( 
	Optional includeAlphaChannel As Boolean = false
) As SolidBrush
```

**VB Usage**<br />
``` VB Usage
Dim includeAlphaChannel As Boolean
Dim returnValue As SolidBrush

returnValue = ColorUtil.GetRandomBrush(includeAlphaChannel)
```

**C++**<br />
``` C++
public:
static SolidBrush^ GetRandomBrush(
	bool includeAlphaChannel = false
)
```

**F#**<br />
``` F#
static member GetRandomBrush : 
        ?includeAlphaChannel : bool 
(* Defaults:
        let _includeAlphaChannel = defaultArg includeAlphaChannel false
*)
-> SolidBrush 

```


#### Parameters
&nbsp;<dl><dt>includeAlphaChannel (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), alpha channel is randomized.</dd></dl>

#### Return Value
Type: SolidBrush<br />The random SolidBrush.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomBrush">GetRandomBrush Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />