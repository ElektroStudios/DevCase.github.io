# NativeMethods.VirtualAllocExNuma Method (IntPtr, UIntPtr, UInt32, MemoryAllocationType, MemoryProtectionOptions, UInt32)
 

Reserves, commits, or changes the state of a region of memory within the virtual address space of the specified process, and specifies the NUMA node for the physical memory. 

 The function initializes the memory it allocates to zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static UIntPtr VirtualAllocExNuma(
	IntPtr hProcess,
	UIntPtr address,
	uint size,
	MemoryAllocationType allocationType,
	MemoryProtectionOptions protection,
	uint nndPreferred
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function VirtualAllocExNuma ( 
	hProcess As IntPtr,
	address As UIntPtr,
	size As UInteger,
	allocationType As MemoryAllocationType,
	protection As MemoryProtectionOptions,
	nndPreferred As UInteger
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim address As UIntPtr
Dim size As UInteger
Dim allocationType As MemoryAllocationType
Dim protection As MemoryProtectionOptions
Dim nndPreferred As UInteger
Dim returnValue As UIntPtr

returnValue = NativeMethods.VirtualAllocExNuma(hProcess, 
	address, size, allocationType, protection, 
	nndPreferred)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static UIntPtr VirtualAllocExNuma(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] UIntPtr address, 
	unsigned int size, 
	MemoryAllocationType allocationType, 
	MemoryProtectionOptions protection, 
	unsigned int nndPreferred
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member VirtualAllocExNuma : 
        hProcess : IntPtr * 
        address : UIntPtr * 
        size : uint32 * 
        allocationType : MemoryAllocationType * 
        protection : MemoryProtectionOptions * 
        nndPreferred : uint32 -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />The handle to a process. 

 The function allocates memory within the virtual address space of this process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access right</dd><dt>address</dt><dd>Type: System.UIntPtr<br />The pointer that specifies a desired starting address for the region of pages that you want to allocate. 

 If you are reserving memory, the function rounds this address down to the nearest multiple of the allocation granularity. 

 If you are committing memory that is already reserved, the function rounds this address down to the nearest page boundary. 

 To determine the size of a page and the allocation granularity on the host computer, use the `GetSystemInfo` function. 

 If *address* is Zero, the function determines where to allocate the region.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the region of memory to allocate, in bytes. 

 If *address* is Zero, the function rounds *size* up to the next page boundary. 

 If *address* is not Zero, the function allocates all pages that contain one or more bytes in the range from *address* to *address*+*size*. This means, for example, that a 2-byte range that straddles a page boundary causes the function to allocate both pages.</dd><dt>allocationType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType</a><br />The type of memory allocation.</dd><dt>protection</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />The memory protection for the region of pages to be allocated. 

 Protection attributes specified when protecting a page cannot conflict with those specified when allocating a page.</dd><dt>nndPreferred</dt><dd>Type: System.UInt32<br />The NUMA node where the physical memory should reside. 

 Used only when allocating a new virtual address (VA) region (either committed or reserved). Otherwise this parameter is ignored when the API is used to commit pages in a region that already exists.</dd></dl>

#### Return Value
Type: UIntPtr<br />If the function succeeds, the return value is the base address of the allocated region of pages. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualallocexnuma" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualallocexnuma</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocExNuma">VirtualAllocExNuma Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />