# GeckoFxUtil.TrimOnMinimize Property 
 

Gets or sets a value that determines whether to mark memory as preferably swappable, from a minimized Mozilla Windows application. 

 When a program is minimized and left for a period of time, Windows will swap memory the program is using from RAM onto the hard disk in anticipation that other programs might need RAM.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool TrimOnMinimize { get; set; }
```

**VB**<br />
``` VB
Public Shared Property TrimOnMinimize As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.TrimOnMinimize

GeckoFxUtil.TrimOnMinimize = value
```

**C++**<br />
``` C++
public:
static property bool TrimOnMinimize {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member TrimOnMinimize : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if swappable memory is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />