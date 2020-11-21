# TweakingUtil.KeyboardDelay Property 
 

Gets or sets the keyboard repeat-delay. From 0 to 3. Where zero sets the shortest delay (approximately 250 ms) and 3 sets the longest delay (approximately 1 second).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int KeyboardDelay { get; set; }
```

**VB**<br />
``` VB
Public Shared Property KeyboardDelay As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.KeyboardDelay

TweakingUtil.KeyboardDelay = value
```

**C++**<br />
``` C++
public:
static property int KeyboardDelay {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member KeyboardDelay : int with get, set

```


#### Property Value
Type: Int32<br />The keyboard repeat-delay, in seconds. From 0 to 3.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 3.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />