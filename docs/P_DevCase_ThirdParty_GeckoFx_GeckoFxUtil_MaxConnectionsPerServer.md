# GeckoFxUtil.MaxConnectionsPerServer Property 
 

Gets or sets the maximum amount of HTTP connections the application can make to a single server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MaxConnectionsPerServer { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MaxConnectionsPerServer As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.MaxConnectionsPerServer

GeckoFxUtil.MaxConnectionsPerServer = value
```

**C++**<br />
``` C++
public:
static property int MaxConnectionsPerServer {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MaxConnectionsPerServer : int with get, set

```


#### Property Value
Type: Int32<br />The maximum amount of HTTP connections the application can make to a single server.

## Remarks
Recommended value: `20`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />