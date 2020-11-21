# NativeMethods.DiscardVirtualMemory Method (IntPtr, IntPtr)
 

Discards the memory contents of a range of memory pages, without decommitting the memory. 

 The contents of discarded memory is undefined and must be rewritten by the application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static Win32ErrorCode DiscardVirtualMemory(
	IntPtr address,
	IntPtr size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function DiscardVirtualMemory ( 
	address As IntPtr,
	size As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.DiscardVirtualMemory(address, 
	size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static Win32ErrorCode DiscardVirtualMemory(
	IntPtr address, 
	IntPtr size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member DiscardVirtualMemory : 
        address : IntPtr * 
        size : IntPtr -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />Page-aligned starting address of the memory to discard.</dd><dt>size</dt><dd>Type: System.IntPtr<br />Size, in bytes, of the memory region to discard. *size* must be an integer multiple of the system page size.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> if successful. Returns a System Error Code (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a>) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-discardvirtualmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-discardvirtualmemory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DiscardVirtualMemory">DiscardVirtualMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />