# TweakingUtil.MinimumSelectedItemsToInvokeMenu Property 
 

Gets or sets a value that determines the minimum items selected in the Explorer to show context menu options that are associated with the selected file extension(s). 

 Valid range is from `1` to `2.147.483.647` (or Int32). 

 Default system value is `15`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MinimumSelectedItemsToInvokeMenu { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MinimumSelectedItemsToInvokeMenu As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.MinimumSelectedItemsToInvokeMenu

TweakingUtil.MinimumSelectedItemsToInvokeMenu = value
```

**C++**<br />
``` C++
public:
static property int MinimumSelectedItemsToInvokeMenu {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MinimumSelectedItemsToInvokeMenu : int with get, set

```


#### Property Value
Type: Int32<br />The minimum items selected in the Explorer to show context menu options that are associated with the selected file extension(s). 

 A value from `1` to `2.147.483.647` (or Int32).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />