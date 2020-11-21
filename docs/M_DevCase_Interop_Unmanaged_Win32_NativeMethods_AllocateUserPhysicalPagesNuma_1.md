# NativeMethods.AllocateUserPhysicalPagesNuma Method (IntPtr, UIntPtr, UIntPtr, UInt32)
 

Allocates physical memory pages to be mapped and unmapped within any Address Windowing Extensions (AWE) region of a specified process and specifies the NUMA node for the physical memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool AllocateUserPhysicalPagesNuma(
	IntPtr hProcess,
	ref UIntPtr refNumberOfPages,
	UIntPtr pageArray,
	uint nndPreferred
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function AllocateUserPhysicalPagesNuma ( 
	hProcess As IntPtr,
	ByRef refNumberOfPages As UIntPtr,
	pageArray As UIntPtr,
	nndPreferred As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refNumberOfPages As UIntPtr
Dim pageArray As UIntPtr
Dim nndPreferred As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.AllocateUserPhysicalPagesNuma(hProcess, 
	refNumberOfPages, pageArray, nndPreferred)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool AllocateUserPhysicalPagesNuma(
	IntPtr hProcess, 
	UIntPtr% refNumberOfPages, 
	UIntPtr pageArray, 
	unsigned int nndPreferred
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member AllocateUserPhysicalPagesNuma : 
        hProcess : IntPtr * 
        refNumberOfPages : UIntPtr byref * 
        pageArray : UIntPtr * 
        nndPreferred : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to a process. 

 The function allocates memory that can later be mapped within the virtual address space of this process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access right.</dd><dt>refNumberOfPages</dt><dd>Type: System.UIntPtr<br />The size of the physical memory to allocate, in pages. 

 To determine the page size of the computer, use the GetSystemInfo function. On output, this parameter receives the number of pages that are actually allocated, which might be less than the number requested.</dd><dt>pageArray</dt><dd>Type: System.UIntPtr<br />A pointer to an array to store the page frame numbers of the allocated memory. 

 The size of the array that is allocated should be at least the *refNumberOfPages* times the size of the ULONG_PTR data type. 

 Caution: Do not attempt to modify this buffer. It contains operating system data, and corruption could be catastrophic. The information in the buffer is not useful to an application.</dd><dt>nndPreferred</dt><dd>Type: System.UInt32<br />The NUMA node where the physical memory should reside.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-allocateuserphysicalpagesnuma" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-allocateuserphysicalpagesnuma</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPagesNuma">AllocateUserPhysicalPagesNuma Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />