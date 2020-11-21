# UIAutomationUtil.ExitThread Method (SafeAccessTokenHandle, UInt32)
 

Terminates the execution of the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ExitThread(
	SafeAccessTokenHandle safeOpenThreadHandle,
	uint exitCode = 0
)
```

**VB**<br />
``` VB
Public Shared Sub ExitThread ( 
	safeOpenThreadHandle As SafeAccessTokenHandle,
	Optional exitCode As UInteger = 0
)
```

**VB Usage**<br />
``` VB Usage
Dim safeOpenThreadHandle As SafeAccessTokenHandle
Dim exitCode As UInteger

UIAutomationUtil.ExitThread(safeOpenThreadHandle, 
	exitCode)
```

**C++**<br />
``` C++
public:
static void ExitThread(
	SafeAccessTokenHandle^ safeOpenThreadHandle, 
	unsigned int exitCode = 0
)
```

**F#**<br />
``` F#
static member ExitThread : 
        safeOpenThreadHandle : SafeAccessTokenHandle * 
        ?exitCode : uint32 
(* Defaults:
        let _exitCode = defaultArg exitCode 0
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>safeOpenThreadHandle</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeAccessTokenHandle<br />An open thread handle. 

 This handle can be obtained calling the <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseThread">PauseThread(ProcessThread)</a> function (or the unmanaged <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThread_1">OpenThread(ThreadAccessRights, Boolean, UInt32)</a> function).</dd><dt>exitCode (Optional)</dt><dd>Type: System.UInt32<br />The desired exit code for the thread.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_ExitThread">ExitThread Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />