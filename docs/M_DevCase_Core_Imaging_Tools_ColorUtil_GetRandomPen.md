# ColorUtil.GetRandomPen Method (Boolean)
 

Generates a random Pen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Pen GetRandomPen(
	bool includeAlphaChannel = false
)
```

**VB**<br />
``` VB
Public Shared Function GetRandomPen ( 
	Optional includeAlphaChannel As Boolean = false
) As Pen
```

**VB Usage**<br />
``` VB Usage
Dim includeAlphaChannel As Boolean
Dim returnValue As Pen

returnValue = ColorUtil.GetRandomPen(includeAlphaChannel)
```

**C++**<br />
``` C++
public:
static Pen^ GetRandomPen(
	bool includeAlphaChannel = false
)
```

**F#**<br />
``` F#
static member GetRandomPen : 
        ?includeAlphaChannel : bool 
(* Defaults:
        let _includeAlphaChannel = defaultArg includeAlphaChannel false
*)
-> Pen 

```


#### Parameters
&nbsp;<dl><dt>includeAlphaChannel (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), alpha channel is randomized.</dd></dl>

#### Return Value
Type: Pen<br />The random Pen.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_ColorUtil">ColorUtil Class</a><br /><a href="Overload_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomPen">GetRandomPen Overload</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />