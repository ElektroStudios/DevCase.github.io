# TweakingUtil.FontSmoothingEnabled Property 
 

Gets or sets a value that enables or disables the font smoothing feature, which uses font antialiasing to make font curves appear smoother by painting pixels at different gray levels.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool FontSmoothingEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property FontSmoothingEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.FontSmoothingEnabled

TweakingUtil.FontSmoothingEnabled = value
```

**C++**<br />
``` C++
public:
static property bool FontSmoothingEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member FontSmoothingEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if font smoothing is enabled, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />