# TweakingUtil.MouseTrailAmount Property 
 

Gets or sets the number of cursors drawn when mouse trail feature is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MouseTrailAmount { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MouseTrailAmount As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.MouseTrailAmount

TweakingUtil.MouseTrailAmount = value
```

**C++**<br />
``` C++
public:
static property int MouseTrailAmount {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MouseTrailAmount : int with get, set

```


#### Property Value
Type: Int32<br />The number of cursors drawn when mouse trail feature is enabled.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 16.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />