# TweakingUtil.WaitToKillAppTimeout Property 
 

Gets or sets the number of milliseconds that the system waits before terminating an application that does not respond to a shutdown request.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int WaitToKillAppTimeout { get; set; }
```

**VB**<br />
``` VB
Public Shared Property WaitToKillAppTimeout As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.WaitToKillAppTimeout

TweakingUtil.WaitToKillAppTimeout = value
```

**C++**<br />
``` C++
public:
static property int WaitToKillAppTimeout {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member WaitToKillAppTimeout : int with get, set

```


#### Property Value
Type: Int32<br />The number of milliseconds that the system waits before terminating an application that does not respond to a shutdown request.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 2147483647;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />