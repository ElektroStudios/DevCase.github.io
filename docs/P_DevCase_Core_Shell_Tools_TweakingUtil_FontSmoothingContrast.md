# TweakingUtil.FontSmoothingContrast Property 
 

Gets or sets the contrast value used in ClearType smoothing. From 1000 to 2200.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int FontSmoothingContrast { get; set; }
```

**VB**<br />
``` VB
Public Shared Property FontSmoothingContrast As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.FontSmoothingContrast

TweakingUtil.FontSmoothingContrast = value
```

**C++**<br />
``` C++
public:
static property int FontSmoothingContrast {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member FontSmoothingContrast : int with get, set

```


#### Property Value
Type: Int32<br />The contrast value used in ClearType smoothing. From 1000 to 2200.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 1000 and 2200.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />