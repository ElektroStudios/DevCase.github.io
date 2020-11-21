# ProcessUtil.SetProcessPrivileges Method (Process, ProcessPrivileges, PrivilegeStates)
 

Enable or disable a process privilege for the specified process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetProcessPrivileges(
	Process pr,
	ProcessPrivileges privileges,
	PrivilegeStates newPrivilegeState
)
```

**VB**<br />
``` VB
Public Shared Sub SetProcessPrivileges ( 
	pr As Process,
	privileges As ProcessPrivileges,
	newPrivilegeState As PrivilegeStates
)
```

**VB Usage**<br />
``` VB Usage
Dim pr As Process
Dim privileges As ProcessPrivileges
Dim newPrivilegeState As PrivilegeStatesProcessUtil.SetProcessPrivileges(pr, privileges, 
	newPrivilegeState)
```

**C++**<br />
``` C++
public:
static void SetProcessPrivileges(
	Process^ pr, 
	ProcessPrivileges privileges, 
	PrivilegeStates newPrivilegeState
)
```

**F#**<br />
``` F#
static member SetProcessPrivileges : 
        pr : Process * 
        privileges : ProcessPrivileges * 
        newPrivilegeState : PrivilegeStates -> unit 

```


#### Parameters
&nbsp;<dl><dt>pr</dt><dd>Type: System.Diagnostics.Process<br />The process identifier.</dd><dt>privileges</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges</a><br />One or more privileges to set.</dd><dt>newPrivilegeState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PrivilegeStates">DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates</a><br />The new state for the privileges.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges">SetProcessPrivileges Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />