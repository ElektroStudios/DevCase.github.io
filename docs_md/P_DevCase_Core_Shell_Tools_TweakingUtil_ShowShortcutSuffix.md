# TweakingUtil.ShowShortcutSuffix Property 
 

Gets or sets a value that determines whether the suffix "shortcut" is shown for new shortcut files (.lnk).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowShortcutSuffix { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowShortcutSuffix As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowShortcutSuffix

TweakingUtil.ShowShortcutSuffix = value
```

**C++**<br />
``` C++
public:
static property bool ShowShortcutSuffix {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowShortcutSuffix : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if shortcut suffix is shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />