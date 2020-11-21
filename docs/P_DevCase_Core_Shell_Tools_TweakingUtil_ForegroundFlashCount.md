# TweakingUtil.ForegroundFlashCount Property 
 

Gets or sets the number of times SetForegroundWindow will flash the taskbar button when rejecting a foreground switch request.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort ForegroundFlashCount { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ForegroundFlashCount As UShort
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As UShort

value = TweakingUtil.ForegroundFlashCount

TweakingUtil.ForegroundFlashCount = value
```

**C++**<br />
``` C++
public:
static property unsigned short ForegroundFlashCount {
	unsigned short get ();
	void set (unsigned short value);
}
```

**F#**<br />
``` F#
static member ForegroundFlashCount : uint16 with get, set

```


#### Property Value
Type: UInt16<br />The number of times SetForegroundWindow will flash the taskbar button when rejecting a foreground switch request.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 65535.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />