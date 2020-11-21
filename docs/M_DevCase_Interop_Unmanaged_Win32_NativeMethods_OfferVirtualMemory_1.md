# NativeMethods.OfferVirtualMemory Method (IntPtr, UInt32, OfferVirtualMemoryPriority)
 

Indicates that the data contained in a range of memory pages is no longer needed by the application and can be discarded by the system if necessary. 

 The specified pages will be marked as inaccessible, removed from the process working set, and will not be written to the paging file. 

 To later reclaim offered pages, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReclaimVirtualMemory">ReclaimVirtualMemory(IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static Win32ErrorCode OfferVirtualMemory(
	IntPtr address,
	uint size,
	OfferVirtualMemoryPriority priority
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function OfferVirtualMemory ( 
	address As IntPtr,
	size As UInteger,
	priority As OfferVirtualMemoryPriority
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As UInteger
Dim priority As OfferVirtualMemoryPriority
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.OfferVirtualMemory(address, 
	size, priority)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static Win32ErrorCode OfferVirtualMemory(
	IntPtr address, 
	unsigned int size, 
	OfferVirtualMemoryPriority priority
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member OfferVirtualMemory : 
        address : IntPtr * 
        size : uint32 * 
        priority : OfferVirtualMemoryPriority -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />Page-aligned starting address of the memory to offer.</dd><dt>size</dt><dd>Type: System.UInt32<br />Size, in bytes, of the memory region to offer. *size* must be an integer multiple of the system page size.</dd><dt>priority</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_OfferVirtualMemoryPriority">DevCase.Interop.Unmanaged.Win32.Enums.OfferVirtualMemoryPriority</a><br />Indicates how important the offered memory is to the application. 

 A higher priority increases the probability that the offered memory can be reclaimed intact when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReclaimVirtualMemory">ReclaimVirtualMemory(IntPtr, IntPtr)</a> function. The system typically discards lower priority memory before discarding higher priority memory.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> if successful. Returns a System Error Code (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a>) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-offervirtualmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-offervirtualmemory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_OfferVirtualMemory">OfferVirtualMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />