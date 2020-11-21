# NativeMethods.VirtualAllocEx Method (IntPtr, IntPtr, UIntPtr, MemoryAllocationType, MemoryProtectionOptions)
 

Reserves, commits, or changes the state of a region of memory within the virtual address space of a specified process. 

 The function initializes the memory it allocates to zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static UIntPtr VirtualAllocEx(
	IntPtr hProcess,
	IntPtr address,
	UIntPtr size,
	MemoryAllocationType allocationType,
	MemoryProtectionOptions protection
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function VirtualAllocEx ( 
	hProcess As IntPtr,
	address As IntPtr,
	size As UIntPtr,
	allocationType As MemoryAllocationType,
	protection As MemoryProtectionOptions
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim address As IntPtr
Dim size As UIntPtr
Dim allocationType As MemoryAllocationType
Dim protection As MemoryProtectionOptions
Dim returnValue As UIntPtr

returnValue = NativeMethods.VirtualAllocEx(hProcess, 
	address, size, allocationType, protection)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static UIntPtr VirtualAllocEx(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] IntPtr address, 
	UIntPtr size, 
	MemoryAllocationType allocationType, 
	MemoryProtectionOptions protection
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member VirtualAllocEx : 
        hProcess : IntPtr * 
        address : IntPtr * 
        size : UIntPtr * 
        allocationType : MemoryAllocationType * 
        protection : MemoryProtectionOptions -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />The handle to a process. 

 The function allocates memory within the virtual address space of this process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> access right</dd><dt>address</dt><dd>Type: System.IntPtr<br />The pointer that specifies a desired starting address for the region of pages that you want to allocate. 

 If you are reserving memory, the function rounds this address down to the nearest multiple of the allocation granularity. 

 If you are committing memory that is already reserved, the function rounds this address down to the nearest page boundary. 

 To determine the size of a page and the allocation granularity on the host computer, use the `GetSystemInfo` function. 

 If *address* is Zero, the function determines where to allocate the region. 

 If this address is within an enclave that you have not initialized by calling `InitializeEnclave` function, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> allocates a page of zeros for the enclave at that address. 

 The page must be previously uncommitted, and will not be measured with the `EEXTEND` instruction of the `Intel Software Guard Extensions` programming model. 

 If the address in within an enclave that you initialized, then the allocation operation fails with the `ERROR_INVALID_ADDRESS` error.</dd><dt>size</dt><dd>Type: System.UIntPtr<br />The size of the region of memory to allocate, in bytes. 

 If *address* is Zero, the function rounds *size* up to the next page boundary. 

 If *address* is not Zero, the function allocates all pages that contain one or more bytes in the range from *address* to *address*+*size*. This means, for example, that a 2-byte range that straddles a page boundary causes the function to allocate both pages.</dd><dt>allocationType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryAllocationType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryAllocationType</a><br />The type of memory allocation.</dd><dt>protection</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">DevCase.Interop.Unmanaged.Win32.Enums.MemoryProtectionOptions</a><br />The memory protection for the region of pages to be allocated. 

 If *address* parameter specifies an address within an enclave, *protection* cannot be any of the following values: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoAccess</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">Guard</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">NoCache</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryProtectionOptions">WriteCombine</a></dd></dl>

#### Return Value
Type: UIntPtr<br />If the function succeeds, the return value is the base address of the allocated region of pages. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366890%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366890%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />