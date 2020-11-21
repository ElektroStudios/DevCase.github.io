# ProcessUtil.SleepThread Method (Int32, TimeSpan)
 

Suspends the specified thread for the given amount of time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SleepThread(
	int threadId,
	TimeSpan timeout
)
```

**VB**<br />
``` VB
Public Shared Sub SleepThread ( 
	threadId As Integer,
	timeout As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim threadId As Integer
Dim timeout As TimeSpanProcessUtil.SleepThread(threadId, timeout)
```

**C++**<br />
``` C++
public:
static void SleepThread(
	int threadId, 
	TimeSpan timeout
)
```

**F#**<br />
``` F#
static member SleepThread : 
        threadId : int * 
        timeout : TimeSpan -> unit 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.Int32<br />The thread identifier.</dd><dt>timeout</dt><dd>Type: System.TimeSpan<br />The amount of time for which the thread is suspended. 

 If the value of the *timeout* argument is Zero, the thread relinquishes the remainder of its time slice to any thread of equal priority that is ready to run.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_SleepThread">SleepThread Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />