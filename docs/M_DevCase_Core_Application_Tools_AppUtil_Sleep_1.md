# AppUtil.Sleep Method (TimeSpan)
 

Blocks the current thread for the specified amount of time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Sleep(
	TimeSpan time
)
```

**VB**<br />
``` VB
Public Shared Sub Sleep ( 
	time As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim time As TimeSpanAppUtil.Sleep(time)
```

**C++**<br />
``` C++
public:
static void Sleep(
	TimeSpan time
)
```

**F#**<br />
``` F#
static member Sleep : 
        time : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>time</dt><dd>Type: System.TimeSpan<br />The amount of time to sleep.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Sleep(TimeSpan.FromSeconds(5))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_Sleep">Sleep Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />