# NativeMethods.SuspendThread32 Method (IntPtr)
 

Suspends the specified 32-Bit thread. 

 A 32-bit application can suspend a 64-Bit thread using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread64">SuspendThread64(SafeAccessTokenHandle)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "Wow64SuspendThread", 
	SetLastError = true)]
public static int SuspendThread32(
	IntPtr hThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "Wow64SuspendThread", 
	SetLastError := true>]
Public Shared Function SuspendThread32 ( 
	hThread As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.SuspendThread32(hThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"Wow64SuspendThread", 
	SetLastError = true)]
static int SuspendThread32(
	IntPtr hThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "Wow64SuspendThread", 
	SetLastError = true)>]
static member SuspendThread32 : 
        hThread : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread that is to be suspended. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SuspendResume</a> access right</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the thread's previous suspend count; otherwise, it is `-1`. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms687400%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms687400%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread32">SuspendThread32 Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />