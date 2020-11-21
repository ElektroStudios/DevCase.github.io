# TweakingUtil.HideDrivesWithNoMedia Property 
 

Gets or sets a value that determines whether drives with no media inserted will be hidden in Explorer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HideDrivesWithNoMedia { get; set; }
```

**VB**<br />
``` VB
Public Shared Property HideDrivesWithNoMedia As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.HideDrivesWithNoMedia

TweakingUtil.HideDrivesWithNoMedia = value
```

**C++**<br />
``` C++
public:
static property bool HideDrivesWithNoMedia {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member HideDrivesWithNoMedia : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if drives with no media inserted are hide, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />