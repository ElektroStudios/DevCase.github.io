# AppUtil.Sleep Method (Int32)
 

Blocks the current thread for the specified amount of time, in milliseconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Sleep(
	int timeout
)
```

**VB**<br />
``` VB
Public Shared Sub Sleep ( 
	timeout As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim timeout As Integer

AppUtil.Sleep(timeout)
```

**C++**<br />
``` C++
public:
static void Sleep(
	int timeout
)
```

**F#**<br />
``` F#
static member Sleep : 
        timeout : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>timeout</dt><dd>Type: System.Int32<br />The amount of time to sleep, in milliseconds.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Sleep(1000)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_Sleep">Sleep Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />