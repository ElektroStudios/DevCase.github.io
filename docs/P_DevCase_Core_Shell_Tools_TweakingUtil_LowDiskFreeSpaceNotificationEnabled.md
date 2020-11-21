# TweakingUtil.LowDiskFreeSpaceNotificationEnabled Property 
 

Gets or sets a value that determines whether a popup will be shown when a hard disk has low disk free space available.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool LowDiskFreeSpaceNotificationEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property LowDiskFreeSpaceNotificationEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.LowDiskFreeSpaceNotificationEnabled

TweakingUtil.LowDiskFreeSpaceNotificationEnabled = value
```

**C++**<br />
``` C++
public:
static property bool LowDiskFreeSpaceNotificationEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member LowDiskFreeSpaceNotificationEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if low disk free space notification is enabled, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />