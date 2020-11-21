# TweakingUtil.MouseHoverTime Property 
 

Gets or sets the time, in milliseconds, that the mouse pointer has to stay in the hover rectangle for TrackMouseEvent to generate a WM_MOUSEHOVER message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int MouseHoverTime { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MouseHoverTime As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = TweakingUtil.MouseHoverTime

TweakingUtil.MouseHoverTime = value
```

**C++**<br />
``` C++
public:
static property int MouseHoverTime {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member MouseHoverTime : int with get, set

```


#### Property Value
Type: Int32<br />The time, in milliseconds, that the mouse pointer has to stay in the hover rectangle for TrackMouseEvent to generate a WM_MOUSEHOVER message.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be greater than 0.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />