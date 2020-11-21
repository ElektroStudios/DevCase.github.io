# GeckoFxUtil.SessionHistoryMaxEntries Property 
 

Gets or sets the maximum amount of pages in the browser's session history.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int SessionHistoryMaxEntries { get; set; }
```

**VB**<br />
``` VB
Public Shared Property SessionHistoryMaxEntries As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = GeckoFxUtil.SessionHistoryMaxEntries

GeckoFxUtil.SessionHistoryMaxEntries = value
```

**C++**<br />
``` C++
public:
static property int SessionHistoryMaxEntries {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member SessionHistoryMaxEntries : int with get, set

```


#### Property Value
Type: Int32<br />The maximum amount of pages in the browser's session history.

## Remarks
Default value: `50`

 Recommended value: `100`

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />