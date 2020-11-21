# TweakingUtil.ShowSuperHiddenFiles Property 
 

Gets or sets a value that determines whether the system should show operating system files.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowSuperHiddenFiles { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowSuperHiddenFiles As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowSuperHiddenFiles

TweakingUtil.ShowSuperHiddenFiles = value
```

**C++**<br />
``` C++
public:
static property bool ShowSuperHiddenFiles {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowSuperHiddenFiles : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operating system files are shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />