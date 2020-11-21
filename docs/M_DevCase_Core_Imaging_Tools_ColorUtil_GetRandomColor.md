# ColorUtil.GetRandomColor Method (Boolean)
 

Generates a random A-RGB color.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Color GetRandomColor(
	bool includeAlphaChannel = false
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomColor ( 
	Optional includeAlphaChannel As Boolean = false
) As Color
```

**VB Usage**<br />
``` VB Usage
Dim includeAlphaChannel As Boolean
Dim returnValue As Color

returnValue = ColorUtil.GetRandomColor(includeAlphaChannel)
```

**C++**<br />
``` C++
public:
static Color GetRandomColor(
	bool includeAlphaChannel = false
)
```

**F#**<br />
``` F#
static member GetRandomColor : 
        ?includeAlphaChannel : bool 
(* Defaults:
        let _includeAlphaChannel = defaultArg includeAlphaChannel false
*)
-> Color 

```


#### Parameters
&nbsp;<dl><dt>includeAlphaChannel (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), alpha channel is randomized.</dd></dl>

#### Return Value
Type: Color<br />The random Color.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomColor">GetRandomColor Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />