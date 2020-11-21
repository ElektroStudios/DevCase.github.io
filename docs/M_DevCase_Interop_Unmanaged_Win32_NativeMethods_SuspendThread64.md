# NativeMethods.SuspendThread64 Method (SafeAccessTokenHandle)
 

Suspends the specified 64-Bit thread. 

 A 64-bit application can suspend a 32-Bit thread using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread32">SuspendThread32(SafeAccessTokenHandle)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "SuspendThread", SetLastError = true)]
public static int SuspendThread64(
	SafeAccessTokenHandle hThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "SuspendThread", SetLastError := true>]
Public Shared Function SuspendThread64 ( 
	hThread As SafeAccessTokenHandle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hThread As SafeAccessTokenHandle
Dim returnValue As Integer

returnValue = NativeMethods.SuspendThread64(hThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"SuspendThread", SetLastError = true)]
static int SuspendThread64(
	SafeAccessTokenHandle^ hThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "SuspendThread", SetLastError = true)>]
static member SuspendThread64 : 
        hThread : SafeAccessTokenHandle -> int 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeAccessTokenHandle<br />A handle to the thread that is to be suspended. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SuspendResume</a> access right</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the thread's previous suspend count; otherwise, it is `-1`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms686345%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms686345%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread64">SuspendThread64 Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />