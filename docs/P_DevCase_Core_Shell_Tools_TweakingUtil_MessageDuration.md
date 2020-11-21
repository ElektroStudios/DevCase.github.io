# TweakingUtil.MessageDuration Property 
 

Gets or sets the time that notification pop-ups should be displayed, in seconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ulong MessageDuration { get; set; }
```

**VB**<br />
``` VB
Public Shared Property MessageDuration As ULong
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As ULong

value = TweakingUtil.MessageDuration

TweakingUtil.MessageDuration = value
```

**C++**<br />
``` C++
public:
static property unsigned long long MessageDuration {
	unsigned long long get ();
	void set (unsigned long long value);
}
```

**F#**<br />
``` F#
static member MessageDuration : uint64 with get, set

```


#### Property Value
Type: UInt64<br />The time that notification pop-ups should be displayed, in seconds.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />