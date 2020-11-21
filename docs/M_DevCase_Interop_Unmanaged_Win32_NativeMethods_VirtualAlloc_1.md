# NativeMethods.VirtualAlloc Method (IntPtr, UIntPtr, MemoryAllocationType, MemoryProtectionOptions)
 

Reserves, commits, or changes the state of a region of pages in the virtual address space of the calling process. 

 Memory allocated by this function is automatically initialized to zero. 

 To allocate memory in the address space of another process, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static UIntPtr VirtualAlloc(
	IntPtr address,
	UIntPtr size,
	MemoryAllocationType allocationType,
	MemoryProtectionOptions protection
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function VirtualAlloc ( 
	address As IntPtr,
	size As UIntPtr,
	allocationType As MemoryAllocationType,
	protection As MemoryProtectionOptions
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As UIntPtr
Dim allocationType As MemoryAllocationType
Dim protection As MemoryProtectionOptions
Dim returnValue As UIntPtr

returnValue = NativeMethods.VirtualAlloc(address, 
	size, allocationType, protection)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static UIntPtr VirtualAlloc(
	IntPtr address, 
	UIntPtr size, 
	MemoryAllocationType allocationType, 
	MemoryProtectionOptions protection
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member VirtualAlloc : 
        address : IntPtr * 
        size : UIntPtr * 
        allocationType : MemoryAllocationType * 
        protection : MemoryProtectionOptions -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />The starting address of the region to allocate. 

 If the memory is being reserved, the specified address is rounded down to the nearest multiple of the allocation granularity. 

 If the memory is already reserved and is being committed, the address is rounded down to the next page boundary. 

 To determine the size of a page and the allocation granularity on the host computer, use the `GetSystemInfo` function. 

 If this parameter is Zero, the system determines where to allocate the region. 

 If this address is within an enclave that you have not initialized by calling `InitializeEnclave`, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> allocates a page of zeros for the enclave at that address. 

 The page must be previously uncommitted, and will not be measured with the `EEXTEND` instruction of the `Intel Software Guard Extensions` programming model. 

 If the address in within an enclave that you initialized, then the allocation operation fails with the `ERROR_INVALID_ADDRESS` error.</dd><dt>size</dt><dd>Type: System.UIntPtr<br />The size of the region, in bytes. 

 If the *address* parameter is Zero, this value is rounded up to the next page boundary. Otherwise, the allocated pages include all pages containing one or more bytes in the range from *address* to *address*+*size*. 

 This means that a 2-byte range straddling a page boundary causes both pages to be included in the allocated region.</dd><dt>allocationType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType</a><br />The type of memory allocation.</dd><dt>protection</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />The memory protection for the region of pages to be allocated. 

 If *address* parameter specifies an address within an enclave, *protection* cannot be any of the following values: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoAccess</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">Guard</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoCache</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">WriteCombine</a></dd></dl>

#### Return Value
Type: UIntPtr<br />If the function succeeds, the return value is the base address of the allocated region of pages. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366887%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366887%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />