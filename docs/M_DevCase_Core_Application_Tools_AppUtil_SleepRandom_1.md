# AppUtil.SleepRandom Method (Int32, Int32)
 

Blocks the current thread for a random amount of time, in milliseconds, between the specified minimum and maximum values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SleepRandom(
	int min,
	int max
)
```

**VB**<br />
``` VB
Public Shared Sub SleepRandom ( 
	min As Integer,
	max As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim min As Integer
Dim max As Integer

AppUtil.SleepRandom(min, max)
```

**C++**<br />
``` C++
public:
static void SleepRandom(
	int min, 
	int max
)
```

**F#**<br />
``` F#
static member SleepRandom : 
        min : int * 
        max : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>min</dt><dd>Type: System.Int32<br />The minimum amount of time to sleep, in milliseconds.</dd><dt>max</dt><dd>Type: System.Int32<br />The maximum amount of time to sleep, in milliseconds.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SleepRandom(min:=1000, max:=5000)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SleepRandom">SleepRandom Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />