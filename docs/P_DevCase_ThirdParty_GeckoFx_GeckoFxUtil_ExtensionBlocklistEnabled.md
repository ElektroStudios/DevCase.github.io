# GeckoFxUtil.ExtensionBlocklistEnabled Property 
 

Gets or sets a value that determines wheter to retrieve a blocklist to restrict extension installation. 

 Mozilla applications will periodically retrieve a blocklist from the server specified in extensions.blocklist.url. 

 While Mozilla 's add-on system is a powerful feature, it can also be a vector for malware. 

 Specific extensions can be blocklisted from a central server (by default, addons.mozilla.org).

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExtensionBlocklistEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ExtensionBlocklistEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.ExtensionBlocklistEnabled

GeckoFxUtil.ExtensionBlocklistEnabled = value
```

**C++**<br />
``` C++
public:
static property bool ExtensionBlocklistEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ExtensionBlocklistEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if extension blocklist is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `false` (`False` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />