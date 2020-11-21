# ProcessUtil.SetProcessPrivileges Method (String, Int32, ProcessPrivileges, PrivilegeStates)
 

Enable or disable a process privilege for the specified process on the target computer. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetProcessPrivileges(
	string computer,
	int pid,
	ProcessPrivileges privileges,
	PrivilegeStates newPrivilegeState
)
```

**VB**<br />
``` VB
Public Shared Sub SetProcessPrivileges ( 
	computer As String,
	pid As Integer,
	privileges As ProcessPrivileges,
	newPrivilegeState As PrivilegeStates
)
```

**VB Usage**<br />
``` VB Usage
Dim computer As String
Dim pid As Integer
Dim privileges As ProcessPrivileges
Dim newPrivilegeState As PrivilegeStatesProcessUtil.SetProcessPrivileges(computer, 
	pid, privileges, newPrivilegeState)
```

**C++**<br />
``` C++
public:
static void SetProcessPrivileges(
	String^ computer, 
	int pid, 
	ProcessPrivileges privileges, 
	PrivilegeStates newPrivilegeState
)
```

**F#**<br />
``` F#
static member SetProcessPrivileges : 
        computer : string * 
        pid : int * 
        privileges : ProcessPrivileges * 
        newPrivilegeState : PrivilegeStates -> unit 

```


#### Parameters
&nbsp;<dl><dt>computer</dt><dd>Type: System.String<br />The computer on which to set the privileges for the process. 

 If this value is empty, it sets the privileges for the current computer.</dd><dt>pid</dt><dd>Type: System.Int32<br />The process identifier (PID).</dd><dt>privileges</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges</a><br />One or more privileges to set.</dd><dt>newPrivilegeState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PrivilegeStates">DevCase.Interop.Unmanaged.Win32.Enums.PrivilegeStates</a><br />The new state for the privileges.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_SetProcessPrivileges">SetProcessPrivileges Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />