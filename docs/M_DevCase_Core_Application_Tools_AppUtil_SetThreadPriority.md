# AppUtil.SetThreadPriority Method (Int32, ThreadPriorityLevel)
 

Sets the priority for the target thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetThreadPriority(
	int index,
	ThreadPriorityLevel priority
)
```

**VB**<br />
``` VB
Public Shared Sub SetThreadPriority ( 
	index As Integer,
	priority As ThreadPriorityLevel
)
```

**VB Usage**<br />
``` VB Usage
Dim index As Integer
Dim priority As ThreadPriorityLevelAppUtil.SetThreadPriority(index, priority)
```

**C++**<br />
``` C++
public:
static void SetThreadPriority(
	int index, 
	ThreadPriorityLevel priority
)
```

**F#**<br />
``` F#
static member SetThreadPriority : 
        index : int * 
        priority : ThreadPriorityLevel -> unit 

```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The thread index.</dd><dt>priority</dt><dd>Type: System.Diagnostics.ThreadPriorityLevel<br />The new thread priority.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetThreadPriority(0, ThreadPriorityLevel.Normal)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_SetThreadPriority">SetThreadPriority Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />