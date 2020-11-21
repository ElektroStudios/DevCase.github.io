# TweakingUtil.ClientAreaAnimationEnabled Property 
 

Gets or sets a value that determines whether animation effects in the client area of applications are enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ClientAreaAnimationEnabled { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ClientAreaAnimationEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = TweakingUtil.ClientAreaAnimationEnabled

TweakingUtil.ClientAreaAnimationEnabled = value
```

**C++**<br />
``` C++
public:
static property bool ClientAreaAnimationEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
static member ClientAreaAnimationEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if effects are enabled, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />