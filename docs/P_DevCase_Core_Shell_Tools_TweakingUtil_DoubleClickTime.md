# TweakingUtil.DoubleClickTime Property 
 

Gets or sets the maximum number of milliseconds that can occur between the first and second clicks of a double-click.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int DoubleClickTime { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DoubleClickTime As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.DoubleClickTime

TweakingUtil.DoubleClickTime = value
```

**C++**<br />
``` C++
public:
static property int DoubleClickTime {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member DoubleClickTime : int with get, set

```


#### Property Value
Type: Int32<br />The maximum number of milliseconds that can occur between the first and second clicks of a double-click.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be greater thaan 0.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />