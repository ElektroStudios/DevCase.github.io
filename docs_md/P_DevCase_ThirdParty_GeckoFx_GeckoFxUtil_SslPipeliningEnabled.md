# GeckoFxUtil.SslPipeliningEnabled Property 
 

Gets or sets a value indicating whether HTTP with SSL pipelining is enabled. 



 Many problems with pipelining are related to broken proxy servers sitting between the user and the destination web site. 

 Since this is not a problem with SSL, it is possible to turn on pipelining for SSL websites only. 

 This preference controls whether to use pipelining for secure websites, regardless of network.http.pipelining.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SslPipeliningEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property SslPipeliningEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.SslPipeliningEnabled

GeckoFxUtil.SslPipeliningEnabled = value
```

**C++**<br />
``` C++
public:
static property bool SslPipeliningEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member SslPipeliningEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if HTTP with SSL pipelining is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />