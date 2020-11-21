# TweakingUtil.ShowOneDriveInMyPC Property 
 

Gets or sets a value that determines whether `One Drive` is visible in `My PC`. 

 This feature is available only in window 10.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowOneDriveInMyPC { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ShowOneDriveInMyPC As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ShowOneDriveInMyPC

TweakingUtil.ShowOneDriveInMyPC = value
```

**C++**<br />
``` C++
public:
static property bool ShowOneDriveInMyPC {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ShowOneDriveInMyPC : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if `One Drive` is visible in `My PC`, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />