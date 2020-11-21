# AppUtil.SleepRandom Method (Int32)
 

Blocks the current thread for a random amount of time, in milliseconds, between `1` and the specified maximum value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SleepRandom(
	int max
)
```

**VB**<br />
``` VB
Public Shared Sub SleepRandom ( 
	max As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim max As Integer

AppUtil.SleepRandom(max)
```

**C++**<br />
``` C++
public:
static void SleepRandom(
	int max
)
```

**F#**<br />
``` F#
static member SleepRandom : 
        max : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>max</dt><dd>Type: System.Int32<br />The maximum amount of time to sleep, in milliseconds.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SleepRandom(max:=5000)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SleepRandom">SleepRandom Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />