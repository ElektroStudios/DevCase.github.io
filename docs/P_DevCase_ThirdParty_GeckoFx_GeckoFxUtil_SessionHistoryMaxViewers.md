# GeckoFxUtil.SessionHistoryMaxViewers Property 
 

Gets or sets the maximum amount of pages that can be stored in memory. 

 Pages that were recently visited are stored in memory in such a way that they don't have to be re-parsed (this is different from the memory cache). 

 This improves performance when pressing `Back` and `Forward` buttons.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SessionHistoryMaxViewers { get; set; }
```

**VB**<br />
``` VB
Public Shared Property SessionHistoryMaxViewers As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.SessionHistoryMaxViewers

GeckoFxUtil.SessionHistoryMaxViewers = value
```

**C++**<br />
``` C++
public:
static property int SessionHistoryMaxViewers {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member SessionHistoryMaxViewers : int with get, set

```


#### Property Value
Type: Int32<br />The maximum amount of pages that can be stored in memory.

## Remarks
Recommended value: `10`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />