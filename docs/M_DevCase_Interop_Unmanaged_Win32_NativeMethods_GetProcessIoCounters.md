# NativeMethods.GetProcessIoCounters Method 
 

Retrieves accounting information for all I/O operations performed by the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool GetProcessIoCounters(
	IntPtr hProcess,
	ref IoCounters refIoCounters
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetProcessIoCounters ( 
	hProcess As IntPtr,
	ByRef refIoCounters As IoCounters
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refIoCounters As IoCounters
Dim returnValue As Boolean

returnValue = NativeMethods.GetProcessIoCounters(hProcess, 
	refIoCounters)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool GetProcessIoCounters(
	IntPtr hProcess, 
	IoCounters% refIoCounters
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetProcessIoCounters : 
        hProcess : IntPtr * 
        refIoCounters : IoCounters byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right. .</dd><dt>refIoCounters</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IoCounters">DevCase.Interop.Unmanaged.Win32.Structures.IoCounters</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IoCounters">IoCounters</a> structure that receives the I/O accounting information for the process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getprocessiocounters" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getprocessiocounters</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />