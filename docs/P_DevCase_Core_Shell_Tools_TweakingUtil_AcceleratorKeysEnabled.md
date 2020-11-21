# TweakingUtil.AcceleratorKeysEnabled Property 
 

Gets or sets a value that determines whether the accelerator keys are enabled. 

 The accelerator keys are visible underlined characters in some menus.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AcceleratorKeysEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property AcceleratorKeysEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.AcceleratorKeysEnabled

TweakingUtil.AcceleratorKeysEnabled = value
```

**C++**<br />
``` C++
public:
static property bool AcceleratorKeysEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member AcceleratorKeysEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the accelerator keys are enabled, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />