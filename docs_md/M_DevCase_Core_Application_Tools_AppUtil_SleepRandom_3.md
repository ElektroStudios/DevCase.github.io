# AppUtil.SleepRandom Method (TimeSpan, TimeSpan)
 

Blocks the current thread for a random amount of time between the specified minimum and maximum values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SleepRandom(
	TimeSpan min,
	TimeSpan max
)
```

**VB**<br />
``` VB
Public Shared Sub SleepRandom ( 
	min As TimeSpan,
	max As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim min As TimeSpan
Dim max As TimeSpanAppUtil.SleepRandom(min, max)
```

**C++**<br />
``` C++
public:
static void SleepRandom(
	TimeSpan min, 
	TimeSpan max
)
```

**F#**<br />
``` F#
static member SleepRandom : 
        min : TimeSpan * 
        max : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>min</dt><dd>Type: System.TimeSpan<br />The minimum amount of time to sleep.</dd><dt>max</dt><dd>Type: System.TimeSpan<br />The maximum amount of time to sleep.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SleepRandom(min:=TimeSpan.FromMilliseconds(1000), max:=TimeSpan.FromMilliseconds(5000))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SleepRandom">SleepRandom Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />