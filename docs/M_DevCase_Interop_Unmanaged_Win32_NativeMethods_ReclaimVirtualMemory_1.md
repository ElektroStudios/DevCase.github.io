# NativeMethods.ReclaimVirtualMemory Method (IntPtr, UInt32)
 

Reclaims a range of memory pages that were offered to the system with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OfferVirtualMemory">OfferVirtualMemory(IntPtr, IntPtr, OfferVirtualMemoryPriority)</a> function. 

 If the offered memory has been discarded, the contents of the memory region is undefined and must be rewritten by the application. 

 If the offered memory has not been discarded, it is reclaimed intact.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static Win32ErrorCode ReclaimVirtualMemory(
	IntPtr address,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ReclaimVirtualMemory ( 
	address As IntPtr,
	size As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.ReclaimVirtualMemory(address, 
	size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static Win32ErrorCode ReclaimVirtualMemory(
	IntPtr address, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member ReclaimVirtualMemory : 
        address : IntPtr * 
        size : uint32 -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />Page-aligned starting address of the memory to reclaim.</dd><dt>size</dt><dd>Type: System.UInt32<br />Size, in bytes, of the memory region to reclaim. *size* must be an integer multiple of the system page size.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> if successful and the memory was reclaimed intact. 

 Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_BUSY</a> if successful but the memory was discarded and must be rewritten by the application. In this case, the contents of the memory region is undefined. 

 Returns a System Error Code (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a>) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-reclaimvirtualmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-reclaimvirtualmemory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReclaimVirtualMemory">ReclaimVirtualMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />