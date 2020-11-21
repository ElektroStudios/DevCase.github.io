# GeckoFxUtil.InitialPaintDelay Property 
 

Gets or sets the amont of milliseconds to wait before first displaying the page. 

 Using keep-alive connections improves performance.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int InitialPaintDelay { get; set; }
```

**VB**<br />
``` VB
Public Shared Property InitialPaintDelay As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.InitialPaintDelay

GeckoFxUtil.InitialPaintDelay = value
```

**C++**<br />
``` C++
public:
static property int InitialPaintDelay {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member InitialPaintDelay : int with get, set

```


#### Property Value
Type: Int32<br />The maximum amount of HTTP keep-alive connections the application can have open at once to a single server.

## Remarks
Default value: `250`

 Recommended value: `100`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />