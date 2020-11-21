# TweakingUtil.HungAppTimeout Property 
 

Gets or sets the number of milliseconds that a thread can go without dispatching a message before the system considers it unresponsive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int HungAppTimeout { get; set; }
```

**VB**<br />
``` VB
Public Shared Property HungAppTimeout As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.HungAppTimeout

TweakingUtil.HungAppTimeout = value
```

**C++**<br />
``` C++
public:
static property int HungAppTimeout {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member HungAppTimeout : int with get, set

```


#### Property Value
Type: Int32<br />The number of milliseconds that a thread can go without dispatching a message before the system considers it unresponsive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 2147483647;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />