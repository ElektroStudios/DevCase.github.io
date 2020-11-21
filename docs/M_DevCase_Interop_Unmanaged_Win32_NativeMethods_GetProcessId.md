# NativeMethods.GetProcessId Method 
 

Retrieves the process identifier (PID) of the specified process handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static int GetProcessId(
	IntPtr handle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GetProcessId ( 
	handle As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.GetProcessId(handle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static int GetProcessId(
	IntPtr handle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GetProcessId : 
        handle : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd></dl>

#### Return Value
Type: Int32<br />The process identifier (PID).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683183%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683183%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />