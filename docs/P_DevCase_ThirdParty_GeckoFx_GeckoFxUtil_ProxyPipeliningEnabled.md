# GeckoFxUtil.ProxyPipeliningEnabled Property 
 

Gets or sets a value indicating whether HTTP pipelining is enabled in proxy servers.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ProxyPipeliningEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ProxyPipeliningEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.ProxyPipeliningEnabled

GeckoFxUtil.ProxyPipeliningEnabled = value
```

**C++**<br />
``` C++
public:
static property bool ProxyPipeliningEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ProxyPipeliningEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if HTTP pipelining is enabled in proxy servers, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />