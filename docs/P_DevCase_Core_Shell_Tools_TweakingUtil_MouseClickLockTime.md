# TweakingUtil.MouseClickLockTime Property 
 

Gets or sets the time delay before the primary mouse button is locked.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MouseClickLockTime { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MouseClickLockTime As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.MouseClickLockTime

TweakingUtil.MouseClickLockTime = value
```

**C++**<br />
``` C++
public:
static property int MouseClickLockTime {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MouseClickLockTime : int with get, set

```


#### Property Value
Type: Int32<br />The time delay before the primary mouse button is locked.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be grater than -1.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />