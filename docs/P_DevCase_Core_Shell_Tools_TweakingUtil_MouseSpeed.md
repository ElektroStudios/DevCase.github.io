# TweakingUtil.MouseSpeed Property 
 

Gets or sets the current mouse speed. From 1 to 20.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MouseSpeed { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MouseSpeed As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.MouseSpeed

TweakingUtil.MouseSpeed = value
```

**C++**<br />
``` C++
public:
static property int MouseSpeed {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MouseSpeed : int with get, set

```


#### Property Value
Type: Int32<br />The current mouse speed. From 1 to 20.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 1 and 20.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />