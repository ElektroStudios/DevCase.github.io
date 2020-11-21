# GeckoFxUtil.DefaultHttpProxy Property 
 

Gets or sets the default HTTP proxy for GeckoFx web-browsers.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static KeyValuePair<string, int> DefaultHttpProxy { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DefaultHttpProxy As KeyValuePair(Of String, Integer)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As KeyValuePair(Of String, Integer)

value = GeckoFxUtil.DefaultHttpProxy

GeckoFxUtil.DefaultHttpProxy = value
```

**C++**<br />
``` C++
public:
static property KeyValuePair<String^, int> DefaultHttpProxy {
	KeyValuePair<String^, int> get ();
	void set (KeyValuePair<String^, int> value);
}
```

**F#**<br />
``` F#
static member DefaultHttpProxy : KeyValuePair<string, int> with get, set

```


#### Property Value
Type: KeyValuePair(String, Int32)<br />The default HTTP proxy.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />