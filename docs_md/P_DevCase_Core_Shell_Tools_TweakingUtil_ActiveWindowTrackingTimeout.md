# TweakingUtil.ActiveWindowTrackingTimeout Property 
 

Gets or sets the active window tracking delay, in milliseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort ActiveWindowTrackingTimeout { get; set; }
```

**VB**<br />
``` VB
Public Shared Property ActiveWindowTrackingTimeout As UShort
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As UShort

value = TweakingUtil.ActiveWindowTrackingTimeout

TweakingUtil.ActiveWindowTrackingTimeout = value
```

**C++**<br />
``` C++
public:
static property unsigned short ActiveWindowTrackingTimeout {
	unsigned short get ();
	void set (unsigned short value);
}
```

**F#**<br />
``` F#
static member ActiveWindowTrackingTimeout : uint16 with get, set

```


#### Property Value
Type: UInt16<br />The active window tracking delay, in milliseconds.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr><tr><td>ArgumentException</td><td>Value should be between 0 and 65535.;value</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />