# NativeMethods.GetProcessIdOfThread Method 
 

Retrieves the process identifier of the process associated with the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static int GetProcessIdOfThread(
	IntPtr threadHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetProcessIdOfThread ( 
	threadHandle As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim threadHandle As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.GetProcessIdOfThread(threadHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static int GetProcessIdOfThread(
	IntPtr threadHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetProcessIdOfThread : 
        threadHandle : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>threadHandle</dt><dd>Type: System.IntPtr<br />A handle to the thread. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryLimitedInformation</a> access right.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the process identifier of the process associated with the specified thread. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms683216.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms683216.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />