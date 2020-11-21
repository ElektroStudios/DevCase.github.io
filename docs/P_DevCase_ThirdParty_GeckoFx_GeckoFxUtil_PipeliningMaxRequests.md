# GeckoFxUtil.PipeliningMaxRequests Property 
 

Gets or sets the maximum amount of requests to pipeline at once when pipelining is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int PipeliningMaxRequests { get; set; }
```

**VB**<br />
``` VB
Public Shared Property PipeliningMaxRequests As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.PipeliningMaxRequests

GeckoFxUtil.PipeliningMaxRequests = value
```

**C++**<br />
``` C++
public:
static property int PipeliningMaxRequests {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member PipeliningMaxRequests : int with get, set

```


#### Property Value
Type: Int32<br />The maximum amount of requests to pipeline at once when pipelining is enabled.

## Remarks
Recommended value: `10`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />