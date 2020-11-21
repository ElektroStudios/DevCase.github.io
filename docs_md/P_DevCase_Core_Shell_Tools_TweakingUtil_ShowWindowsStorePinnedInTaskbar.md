# TweakingUtil.ShowWindowsStorePinnedInTaskbar Property 
 

Gets or sets a value that determines whether Windows Store pinned item will be shown in Taskbar. 

 This feature is available only in window 10.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowWindowsStorePinnedInTaskbar { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowWindowsStorePinnedInTaskbar As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowWindowsStorePinnedInTaskbar

TweakingUtil.ShowWindowsStorePinnedInTaskbar = value
```

**C++**<br />
``` C++
public:
static property bool ShowWindowsStorePinnedInTaskbar {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowWindowsStorePinnedInTaskbar : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if Windows Store pinned item is shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />