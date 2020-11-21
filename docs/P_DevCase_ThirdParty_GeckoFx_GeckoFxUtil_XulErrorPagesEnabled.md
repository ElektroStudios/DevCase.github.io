# GeckoFxUtil.XulErrorPagesEnabled Property 
 

Gets or sets a value that determines wheter xul error pages are enabled. 

 If xul error pages are disabled, the alert dialogue does not provide any means to override/ignore the error. 

 If xul error pages are enabld, you are given the option to override the error and walked through the process quite nicely.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool XulErrorPagesEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property XulErrorPagesEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.XulErrorPagesEnabled

GeckoFxUtil.XulErrorPagesEnabled = value
```

**C++**<br />
``` C++
public:
static property bool XulErrorPagesEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member XulErrorPagesEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if extension blocklist is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />