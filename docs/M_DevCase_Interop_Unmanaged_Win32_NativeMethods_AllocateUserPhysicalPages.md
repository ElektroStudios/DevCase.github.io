# NativeMethods.AllocateUserPhysicalPages Method (IntPtr, IntPtr, IntPtr)
 

Allocates physical memory pages to be mapped and unmapped within any Address Windowing Extensions (AWE) region of a specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool AllocateUserPhysicalPages(
	IntPtr hProcess,
	ref IntPtr refNumberOfPages,
	IntPtr pageArray
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function AllocateUserPhysicalPages ( 
	hProcess As IntPtr,
	ByRef refNumberOfPages As IntPtr,
	pageArray As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refNumberOfPages As IntPtr
Dim pageArray As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.AllocateUserPhysicalPages(hProcess, 
	refNumberOfPages, pageArray)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool AllocateUserPhysicalPages(
	IntPtr hProcess, 
	IntPtr% refNumberOfPages, 
	IntPtr pageArray
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member AllocateUserPhysicalPages : 
        hProcess : IntPtr * 
        refNumberOfPages : IntPtr byref * 
        pageArray : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to a process. 

 The function allocates memory that can later be mapped within the virtual address space of this process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access right.</dd><dt>refNumberOfPages</dt><dd>Type: System.IntPtr<br />The size of the physical memory to allocate, in pages. 

 To determine the page size of the computer, use the GetSystemInfo function. On output, this parameter receives the number of pages that are actually allocated, which might be less than the number requested.</dd><dt>pageArray</dt><dd>Type: System.IntPtr<br />A pointer to an array to store the page frame numbers of the allocated memory. 

 The size of the array that is allocated should be at least the *refNumberOfPages* times the size of the ULONG_PTR data type. 

 Caution: Do not attempt to modify this buffer. It contains operating system data, and corruption could be catastrophic. The information in the buffer is not useful to an application.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-allocateuserphysicalpages" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-allocateuserphysicalpages</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPages">AllocateUserPhysicalPages Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />