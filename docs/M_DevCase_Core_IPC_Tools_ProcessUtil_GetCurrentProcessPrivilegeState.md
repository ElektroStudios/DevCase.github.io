# ProcessUtil.GetCurrentProcessPrivilegeState Method (ProcessPrivileges)
 

Gets the state of a privilege from the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PrivilegeStates GetCurrentProcessPrivilegeState(
	ProcessPrivileges privilege
)
```

**VB**<br />
``` VB
Public Shared Function GetCurrentProcessPrivilegeState ( 
	privilege As ProcessPrivileges
) As PrivilegeStates
```

**VB Usage**<br />
``` VB Usage
Dim privilege As ProcessPrivileges
Dim returnValue As PrivilegeStates

returnValue = ProcessUtil.GetCurrentProcessPrivilegeState(privilege)
```

**C++**<br />
``` C++
public:
static PrivilegeStates GetCurrentProcessPrivilegeState(
	ProcessPrivileges privilege
)
```

**F#**<br />
``` F#
static member GetCurrentProcessPrivilegeState : 
        privilege : ProcessPrivileges -> PrivilegeStates 

```


#### Parameters
&nbsp;<dl><dt>privilege</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessPrivileges">DevCase.Interop.Unmanaged.Win32.Enums.ProcessPrivileges</a><br />The privileges to check.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PrivilegeStates">PrivilegeStates</a><br />The privilege state.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_ProcessUtil_GetCurrentProcessPrivilegeState">GetCurrentProcessPrivilegeState Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />