# NativeMethods.GetPriorityClass Method 
 

Retrieves the priority class for the specified process. 

 This value, together with the priority value of each thread of the process, determines each thread's base priority level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static ProcessPriorityClass GetPriorityClass(
	IntPtr hProcess
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetPriorityClass ( 
	hProcess As IntPtr
) As ProcessPriorityClass
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim returnValue As ProcessPriorityClass

returnValue = NativeMethods.GetPriorityClass(hProcess)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static ProcessPriorityClass GetPriorityClass(
	IntPtr hProcess
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetPriorityClass : 
        hProcess : IntPtr -> ProcessPriorityClass 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 This handle must be created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd></dl>

#### Return Value
Type: ProcessPriorityClass<br />If the function succeeds, the return value is the priority class of the specified process. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683211%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683211%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />