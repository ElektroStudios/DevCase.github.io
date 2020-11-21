# ProcessUtil.SetCurrentProcessCriticalState Method 
 

Sets the critical state for the caller process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetCurrentProcessCriticalState(
	ProcessCriticalState state
)
```

**VB**<br />
``` VB
Public Shared Sub SetCurrentProcessCriticalState ( 
	state As ProcessCriticalState
)
```

**VB Usage**<br />
``` VB Usage
Dim state As ProcessCriticalStateProcessUtil.SetCurrentProcessCriticalState(state)
```

**C++**<br />
``` C++
public:
static void SetCurrentProcessCriticalState(
	ProcessCriticalState state
)
```

**F#**<br />
``` F#
static member SetCurrentProcessCriticalState : 
        state : ProcessCriticalState -> unit 

```


#### Parameters
&nbsp;<dl><dt>state</dt><dd>Type: <a href="T_DevCase_Core_IPC_ProcessCriticalState">DevCase.Core.IPC.ProcessCriticalState</a><br />The new critical state.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>state</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />