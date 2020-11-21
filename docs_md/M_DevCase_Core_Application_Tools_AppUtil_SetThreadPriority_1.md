# AppUtil.SetThreadPriority Method (ThreadPriority)
 

Sets the priority for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetThreadPriority(
	ThreadPriority priority
)
```

**VB**<br />
``` VB
Public Shared Sub SetThreadPriority ( 
	priority As ThreadPriority
)
```

**VB Usage**<br />
``` VB Usage
Dim priority As ThreadPriorityAppUtil.SetThreadPriority(priority)
```

**C++**<br />
``` C++
public:
static void SetThreadPriority(
	ThreadPriority priority
)
```

**F#**<br />
``` F#
static member SetThreadPriority : 
        priority : ThreadPriority -> unit 

```


#### Parameters
&nbsp;<dl><dt>priority</dt><dd>Type: System.Threading.ThreadPriority<br />The new thread priority.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetThreadPriority(ThreadPriorityLevel.Normal)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SetThreadPriority">SetThreadPriority Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />