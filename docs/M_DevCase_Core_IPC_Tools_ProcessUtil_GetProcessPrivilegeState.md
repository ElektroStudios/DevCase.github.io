# ProcessUtil.GetProcessPrivilegeState Method (Process, ProcessPrivileges)
 

Gets the state of a privilege from the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PrivilegeStates GetProcessPrivilegeState(
	Process pr,
	ProcessPrivileges privilege
)
```

**VB**<br />
``` VB
Public Shared Function GetProcessPrivilegeState ( 
	pr As Process,
	privilege As ProcessPrivileges
) As PrivilegeStates
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim privilege As ProcessPrivileges
Dim returnValue As PrivilegeStates

returnValue = ProcessUtil.GetProcessPrivilegeState(pr, 
	privilege)
```

**C++**<br />
``` C++
public:
static PrivilegeStates GetProcessPrivilegeState(
	Process^ pr, 
	ProcessPrivileges privilege
)
```

**F#**<br />
``` F#
static member GetProcessPrivilegeState : 
        pr : Process * 
        privilege : ProcessPrivileges -> PrivilegeStates 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The process.</dd><dt>privilege</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges</a><br />The privileges to check.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PrivilegeStates">PrivilegeStates</a><br />The privilege state.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />