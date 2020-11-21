# NativeMethods.GetProcessWorkingSetSize Method 
 

Retrieves the minimum and maximum working set sizes of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetProcessWorkingSetSize(
	IntPtr hProcess,
	out IntPtr refMinimumWorkingSetSize,
	out IntPtr refMaximumWorkingSetSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetProcessWorkingSetSize ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refMinimumWorkingSetSize As IntPtr,
	<OutAttribute> ByRef refMaximumWorkingSetSize As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refMinimumWorkingSetSize As IntPtr
Dim refMaximumWorkingSetSize As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.GetProcessWorkingSetSize(hProcess, 
	refMinimumWorkingSetSize, refMaximumWorkingSetSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetProcessWorkingSetSize(
	[InAttribute] IntPtr hProcess, 
	[OutAttribute] IntPtr% refMinimumWorkingSetSize, 
	[OutAttribute] IntPtr% refMaximumWorkingSetSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetProcessWorkingSetSize : 
        hProcess : IntPtr * 
        refMinimumWorkingSetSize : IntPtr byref * 
        refMaximumWorkingSetSize : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refMinimumWorkingSetSize</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the minimum working set size of the specified process, in bytes. 

 The virtual memory manager attempts to keep at least this much memory resident in the process whenever the process is active.</dd><dt>refMaximumWorkingSetSize</dt><dd>Type: System.IntPtr<br />A pointer to a variable that receives the maximum working set size of the specified process, in bytes. 

 The virtual memory manager attempts to keep no more than this much memory resident in the process whenever the process is active when memory is in short supply.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getprocessworkingsetsize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getprocessworkingsetsize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />