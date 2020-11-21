# NativeMethods.ResumeThread Method (SafeAccessTokenHandle)
 

Decrements a thread's suspend count. 

 When the suspend count is decremented to zero, the execution of the thread is resumed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static int ResumeThread(
	SafeAccessTokenHandle hThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ResumeThread ( 
	hThread As SafeAccessTokenHandle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hThread As SafeAccessTokenHandle
Dim returnValue As Integer

returnValue = NativeMethods.ResumeThread(hThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static int ResumeThread(
	SafeAccessTokenHandle^ hThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ResumeThread : 
        hThread : SafeAccessTokenHandle -> int 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeAccessTokenHandle<br />A handle to the thread to be resumed. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SuspendResume</a> access right</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the thread's previous suspend count; otherwise, it is `-1`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms685086%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms685086%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ResumeThread">ResumeThread Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />