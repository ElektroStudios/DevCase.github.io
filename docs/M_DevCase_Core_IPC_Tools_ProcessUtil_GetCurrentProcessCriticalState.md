# ProcessUtil.GetCurrentProcessCriticalState Method 
 

Determines whether the caller process is considered `critical`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessCriticalState GetCurrentProcessCriticalState()
```

**VB**<br />
``` VB
Public Shared Function GetCurrentProcessCriticalState As ProcessCriticalState
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ProcessCriticalState

returnValue = ProcessUtil.GetCurrentProcessCriticalState()
```

**C++**<br />
``` C++
public:
static ProcessCriticalState GetCurrentProcessCriticalState()
```

**F#**<br />
``` F#
static member GetCurrentProcessCriticalState : unit -> ProcessCriticalState 

```


#### Return Value
Type: <a href="T_DevCase_Core_IPC_ProcessCriticalState">ProcessCriticalState</a><br />A <a href="T_DevCase_Core_IPC_ProcessCriticalState">ProcessCriticalState</a> enumeration value indicating the critical state.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />