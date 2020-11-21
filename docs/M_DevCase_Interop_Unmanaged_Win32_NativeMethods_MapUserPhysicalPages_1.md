# NativeMethods.MapUserPhysicalPages Method (IntPtr, UIntPtr, UIntPtr)
 

Maps previously allocated physical memory pages at a specified address in an Address Windowing Extensions (AWE) region. 

 The contents of discarded memory is undefined and must be rewritten by the application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool MapUserPhysicalPages(
	IntPtr address,
	ref UIntPtr refNumberOfPages,
	UIntPtr pageArray
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function MapUserPhysicalPages ( 
	address As IntPtr,
	ByRef refNumberOfPages As UIntPtr,
	pageArray As UIntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim refNumberOfPages As UIntPtr
Dim pageArray As UIntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.MapUserPhysicalPages(address, 
	refNumberOfPages, pageArray)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool MapUserPhysicalPages(
	[InAttribute] IntPtr address, 
	UIntPtr% refNumberOfPages, 
	[InAttribute] UIntPtr pageArray
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member MapUserPhysicalPages : 
        address : IntPtr * 
        refNumberOfPages : UIntPtr byref * 
        pageArray : UIntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />A pointer to the starting address of the region of memory to remap. 

 The value of *address* must be within the address range that the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function returns when the Address Windowing Extensions (AWE) region is allocated.</dd><dt>refNumberOfPages</dt><dd>Type: System.UIntPtr<br />The size of the physical memory and virtual address space for which to establish translations, in pages. 

 The virtual address range is contiguous starting at *address*. The physical frames are specified by the *pageArray*. 

 The total number of pages cannot extend from the starting address beyond the end of the range that is specified in <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPages">AllocateUserPhysicalPages(IntPtr, IntPtr, IntPtr)</a>.</dd><dt>pageArray</dt><dd>Type: System.UIntPtr<br />A pointer to an array of physical page frame numbers. 

 These frames are mapped by the argument *address* on return from this function. 

 The size of the memory that is allocated should be at least the *refNumberOfPages* times the size of the data type ULONG_PTR. 

 Caution: Do not attempt to modify this buffer. It contains operating system data, and corruption could be catastrophic. The information in the buffer is not useful to an application.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic) and no mapping is done—partial or otherwise. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-mapuserphysicalpages" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-mapuserphysicalpages</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapUserPhysicalPages">MapUserPhysicalPages Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />