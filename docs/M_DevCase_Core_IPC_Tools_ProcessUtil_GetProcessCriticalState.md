# ProcessUtil.GetProcessCriticalState Method 
 

Determines whether the specified process is considered critical.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessCriticalState GetProcessCriticalState(
	IntPtr handle
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessCriticalState ( 
	handle As IntPtr
) As ProcessCriticalState
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim returnValue As ProcessCriticalState

returnValue = ProcessUtil.GetProcessCriticalState(handle)
```

**C++**<br />
``` C++
public:
static ProcessCriticalState GetProcessCriticalState(
	IntPtr handle
)
```

**F#**<br />
``` F#
static member GetProcessCriticalState : 
        handle : IntPtr -> ProcessCriticalState 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle (IntPtr) to the process to query.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IPC_ProcessCriticalState">ProcessCriticalState</a><br />A <a href="T_DevCase_Core_IPC_ProcessCriticalState">ProcessCriticalState</a> enumeration value indicating the critical state.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />