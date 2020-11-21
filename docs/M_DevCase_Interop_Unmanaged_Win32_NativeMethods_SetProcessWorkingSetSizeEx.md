# NativeMethods.SetProcessWorkingSetSizeEx Method 
 

Sets the minimum and maximum working set sizes for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool SetProcessWorkingSetSizeEx(
	IntPtr hProcess,
	IntPtr minWorkingSetSize,
	IntPtr maxWorkingSetSize,
	SetProcessWorkingSetSizeFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetProcessWorkingSetSizeEx ( 
	hProcess As IntPtr,
	minWorkingSetSize As IntPtr,
	maxWorkingSetSize As IntPtr,
	flags As SetProcessWorkingSetSizeFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim minWorkingSetSize As IntPtr
Dim maxWorkingSetSize As IntPtr
Dim flags As SetProcessWorkingSetSizeFlags
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessWorkingSetSizeEx(hProcess, 
	minWorkingSetSize, maxWorkingSetSize, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool SetProcessWorkingSetSizeEx(
	IntPtr hProcess, 
	IntPtr minWorkingSetSize, 
	IntPtr maxWorkingSetSize, 
	SetProcessWorkingSetSizeFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetProcessWorkingSetSizeEx : 
        hProcess : IntPtr * 
        minWorkingSetSize : IntPtr * 
        maxWorkingSetSize : IntPtr * 
        flags : SetProcessWorkingSetSizeFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process whose working set sizes is to be set. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">SetQuota</a> access rights.</dd><dt>minWorkingSetSize</dt><dd>Type: System.IntPtr<br />The minimum working set size for the process, in bytes. 

 The virtual memory manager attempts to keep at least this much memory resident in the process whenever the process is active. 

 This parameter must be greater than 0 but less than or equal to the maximum working set size. The default size is 50 pages (for example, this is 204,800 bytes on systems with a 4K page size). If the value is greater than 0 but less than 20 pages, the minimum value is set to 20 pages. 

 If both *minWorkingSetSize* and *maxWorkingSetSize* have the value `IntPtr(-1)`, the function removes as many pages as possible from the working set of the specified process.</dd><dt>maxWorkingSetSize</dt><dd>Type: System.IntPtr<br />The maximum working set size for the process, in bytes. 

 The virtual memory manager attempts to keep no more than this much memory resident in the process whenever the process is active and available memory is low. 

 This parameter must be greater than or equal to 13 pages (for example, 53,248 on systems with a 4K page size), and less than the system-wide maximum (number of available pages minus 512 pages). The default size is 345 pages (for example, this is 1,413,120 bytes on systems with a 4K page size). 

 If both *minWorkingSetSize* and *maxWorkingSetSize* have the value `IntPtr(-1)`, the function removes as many pages as possible from the working set of the specified process.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SetProcessWorkingSetSizeFlags">DevCase.Interop.Unmanaged.Win32.Enums.SetProcessWorkingSetSizeFlags</a><br />The flags that control the enforcement of the minimum and maximum working set sizes.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-setprocessworkingsetsizeex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-setprocessworkingsetsizeex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />