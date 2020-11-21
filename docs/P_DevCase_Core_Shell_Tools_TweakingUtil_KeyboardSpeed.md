# TweakingUtil.KeyboardSpeed Property 
 

Gets or sets the keyboard repeat-speed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int KeyboardSpeed { get; set; }
```

**VB**<br />
``` VB
Public Shared Property KeyboardSpeed As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.KeyboardSpeed

TweakingUtil.KeyboardSpeed = value
```

**C++**<br />
``` C++
public:
static property int KeyboardSpeed {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member KeyboardSpeed : int with get, set

```


#### Property Value
Type: Int32<br />The keyboard repeat-speed, from 0 to 31.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 31.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />