# GeckoFxUtil.ExposePluginFullPath Property 
 

Gets or sets a value indicating whether to expose the full path of a installed plugin file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ExposePluginFullPath { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ExposePluginFullPath As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GeckoFxUtil.ExposePluginFullPath

GeckoFxUtil.ExposePluginFullPath = value
```

**C++**<br />
``` C++
public:
static property bool ExposePluginFullPath {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ExposePluginFullPath : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if exposing the pluging fullpath is enabled, otherwise, `false` (`False` in Visual Basic).

## Remarks
Recommended value: `true` (`True` in Visual Basic)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_GeckoFxUtil">GeckoFxUtil Class</a><br /><a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />