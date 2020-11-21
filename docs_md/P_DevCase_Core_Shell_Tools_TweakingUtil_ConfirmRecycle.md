# TweakingUtil.ConfirmRecycle Property 
 

Gets or sets a value that determines whether the system will show a confirmation dialog box when deleting items to the Recycle Bin.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ConfirmRecycle { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ConfirmRecycle As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ConfirmRecycle

TweakingUtil.ConfirmRecycle = value
```

**C++**<br />
``` C++
public:
static property bool ConfirmRecycle {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ConfirmRecycle : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if recycle confirmation dialog box is shown, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />