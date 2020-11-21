# NativeMethods.VirtualFree Method (IntPtr, IntPtr, MemoryFreeType)
 

Releases, decommits, or releases and decommits a region of pages within the virtual address space of the calling process. 

 To free memory allocated in another process by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAllocEx">VirtualAllocEx(IntPtr, IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualFreeEx">VirtualFreeEx(IntPtr, IntPtr, IntPtr, MemoryFreeType)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool VirtualFree(
	IntPtr address,
	IntPtr size,
	MemoryFreeType freeType
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function VirtualFree ( 
	address As IntPtr,
	size As IntPtr,
	freeType As MemoryFreeType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As IntPtr
Dim freeType As MemoryFreeType
Dim returnValue As Boolean

returnValue = NativeMethods.VirtualFree(address, 
	size, freeType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool VirtualFree(
	[InAttribute] IntPtr address, 
	IntPtr size, 
	MemoryFreeType freeType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member VirtualFree : 
        address : IntPtr * 
        size : IntPtr * 
        freeType : MemoryFreeType -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />A pointer to the base address of the region of pages to be freed. 

 If the *freeType* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryFreeType">Release</a>, this parameter must be the base address returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function when the region of pages is reserved.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The size of the region of memory to be freed, in bytes. 

 If the *freeType* parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryFreeType">Release</a>, this parameter must be `0` (zero). 

 The function frees the entire region that is reserved in the initial allocation call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> function. 

 If the dwFreeType parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryFreeType">Decommit</a>, the function decommits all memory pages that contain one or more bytes in the range from the `address` parameter to (`address`+`size`). This means, for example, that a 2-byte region of memory that straddles a page boundary causes both pages to be decommitted. 

 If `address` parameter is the base address returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a> and `size` parameter is `0` (zero), the function decommits the entire region that is allocated by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualAlloc">VirtualAlloc(IntPtr, IntPtr, MemoryAllocationType, MemoryProtectionOptions)</a>. After that, the entire region is in the reserved state.</dd><dt>freeType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MemoryFreeType">DevCase.Interop.Unmanaged.Win32.Enums.MemoryFreeType</a><br />The type of free operation.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366892%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366892%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualFree">VirtualFree Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />