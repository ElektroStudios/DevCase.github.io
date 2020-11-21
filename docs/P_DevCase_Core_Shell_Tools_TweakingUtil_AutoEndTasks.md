# TweakingUtil.AutoEndTasks Property 
 

Gets or sets a value that determines whether user processes end automatically when the user either logs off or shuts down.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AutoEndTasks { get; set; }
```

**VB**<br />
``` VB
Public Shared Property AutoEndTasks As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.AutoEndTasks

TweakingUtil.AutoEndTasks = value
```

**C++**<br />
``` C++
public:
static property bool AutoEndTasks {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member AutoEndTasks : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if user processes end automatically when the user either logs off or shuts down, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-2000-server/cc978604(v=technet.10)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-2000-server/cc978604(v=technet.10)</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />