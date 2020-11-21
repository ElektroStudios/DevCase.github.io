# TweakingUtil.HotTrackingEnabled Property 
 

Gets or sets a value that determines whether hot tracking of user-interface elements such as menu names on menu bars is enabled. Hot-tracking means that when the cursor moves over an item, it is highlighted but not selected.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HotTrackingEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property HotTrackingEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.HotTrackingEnabled

TweakingUtil.HotTrackingEnabled = value
```

**C++**<br />
``` C++
public:
static property bool HotTrackingEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member HotTrackingEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if enabled, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />