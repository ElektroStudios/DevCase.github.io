# TweakingUtil.ScreensaverTimeout Property 
 

Gets or sets the screen saver time-out, in seconds. From 1 to 599940.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int ScreensaverTimeout { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ScreensaverTimeout As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.ScreensaverTimeout

TweakingUtil.ScreensaverTimeout = value
```

**C++**<br />
``` C++
public:
static property int ScreensaverTimeout {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member ScreensaverTimeout : int with get, set

```


#### Property Value
Type: Int32<br />The screen saver time-out, in seconds. From 1 to 599940.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 1 and 599940.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />