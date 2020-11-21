# TweakingUtil.ShowFrequentDirsInQuickAccess Property 
 

Gets or sets a value that determines whether frequent directories are shown in the Quick Access dialog. 

 This feature is available only in window 10.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowFrequentDirsInQuickAccess { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowFrequentDirsInQuickAccess As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowFrequentDirsInQuickAccess

TweakingUtil.ShowFrequentDirsInQuickAccess = value
```

**C++**<br />
``` C++
public:
static property bool ShowFrequentDirsInQuickAccess {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowFrequentDirsInQuickAccess : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if frequent directories are shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />