# NativeMethods.PrefetchVirtualMemory Method 
 

Provides an efficient mechanism to bring into memory potentially discontiguous virtual address ranges in a process address space.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool PrefetchVirtualMemory(
	IntPtr hProcess,
	UIntPtr numberOfEntries,
	IntPtr addresses,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function PrefetchVirtualMemory ( 
	hProcess As IntPtr,
	numberOfEntries As UIntPtr,
	addresses As IntPtr,
	flags As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim numberOfEntries As UIntPtr
Dim addresses As IntPtr
Dim flags As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PrefetchVirtualMemory(hProcess, 
	numberOfEntries, addresses, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool PrefetchVirtualMemory(
	IntPtr hProcess, 
	UIntPtr numberOfEntries, 
	IntPtr addresses, 
	unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member PrefetchVirtualMemory : 
        hProcess : IntPtr * 
        numberOfEntries : UIntPtr * 
        addresses : IntPtr * 
        flags : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process whose virtual address ranges are to be prefetched.</dd><dt>numberOfEntries</dt><dd>Type: System.UIntPtr<br />Number of entries in the array pointed to by the *addresses* parameter.</dd><dt>addresses</dt><dd>Type: System.IntPtr<br />Pointer to an array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32MemoryRangeEntry">Win32MemoryRangeEntry</a> structures which each specify a virtual address range to be prefetched. 

 The virtual address ranges may cover any part of the process address space accessible by the target process.</dd><dt>flags</dt><dd>Type: System.UInt32<br />Reserved parameter. Must be 0.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-prefetchvirtualmemory" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-prefetchvirtualmemory</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />