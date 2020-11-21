# GeckoFxUtil.PipeliningEnabled Property 
 

Gets or sets a value indicating whether HTTP pipelining is enabled. 



 Pipelining reduces network load and can reduce page loading times over high-latency connections, but not all servers support it. 

 Some servers may even behave incorrectly if they receive pipelined requests. 

 If a proxy server is not configured, this preference controls whether to attempt to use pipelining.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PipeliningEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property PipeliningEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.PipeliningEnabled

GeckoFxUtil.PipeliningEnabled = value
```

**C++**<br />
``` C++
public:
static property bool PipeliningEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member PipeliningEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if HTTP pipelining is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />