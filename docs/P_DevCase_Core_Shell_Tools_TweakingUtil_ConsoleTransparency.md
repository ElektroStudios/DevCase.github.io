# TweakingUtil.ConsoleTransparency Property 
 

Gets or sets a value that determines the transparency of the CMD, valid range is from `0.0F` to `1.0F`. 

 This feature is available only in window 10 and the new Console should be enabled, see <a href="P_DevCase_Core_Shell_Tools_TweakingUtil_Consolev2Enabled">Consolev2Enabled</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static float ConsoleTransparency { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ConsoleTransparency As Single
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Single

value = TweakingUtil.ConsoleTransparency

TweakingUtil.ConsoleTransparency = value
```

**C++**<br />
``` C++
public:
static property float ConsoleTransparency {
	float get ();
	void set (float value);
}
```

**F#**<br />
``` F#
static member ConsoleTransparency : float32 with get, set

```


#### Property Value
Type: Single<br />The transparency of the CMD, from `0.0F` to `1.0F`.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />