# NativeMethods.TerminateThread Method (SafeAccessTokenHandle, UInt32)
 

Terminates a thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool TerminateThread(
	SafeAccessTokenHandle hThread,
	uint dwExitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function TerminateThread ( 
	hThread As SafeAccessTokenHandle,
	dwExitCode As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As SafeAccessTokenHandle
Dim dwExitCode As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.TerminateThread(hThread, 
	dwExitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool TerminateThread(
	SafeAccessTokenHandle^ hThread, 
	unsigned int dwExitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member TerminateThread : 
        hThread : SafeAccessTokenHandle * 
        dwExitCode : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeAccessTokenHandle<br />A handle to the thread to be terminated. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">Terminate</a> access right.</dd><dt>dwExitCode</dt><dd>Type: System.UInt32<br />The exit code for the thread. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeThread">GetExitCodeThread(IntPtr, UInt32)</a> function to retrieve a thread's exit value.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms686717%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms686717%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_TerminateThread">TerminateThread Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />