# NativeMethods.FreeUserPhysicalPages Method (IntPtr, IntPtr, IntPtr)
 

Frees physical memory pages that are allocated previously by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPages">AllocateUserPhysicalPages(IntPtr, IntPtr, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AllocateUserPhysicalPagesNuma">AllocateUserPhysicalPagesNuma(IntPtr, IntPtr, IntPtr, UInt32)</a>. 

 If any of these pages are currently mapped in the Address Windowing Extensions (AWE) region, they are automatically unmapped by this call. 

 This does not affect the virtual address space that is occupied by a specified Address Windowing Extensions (AWE) region.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool FreeUserPhysicalPages(
	IntPtr hProcess,
	ref IntPtr refNumberOfPages,
	IntPtr pageArray
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function FreeUserPhysicalPages ( 
	hProcess As IntPtr,
	ByRef refNumberOfPages As IntPtr,
	pageArray As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refNumberOfPages As IntPtr
Dim pageArray As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FreeUserPhysicalPages(hProcess, 
	refNumberOfPages, pageArray)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool FreeUserPhysicalPages(
	[InAttribute] IntPtr hProcess, 
	IntPtr% refNumberOfPages, 
	[InAttribute] IntPtr pageArray
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member FreeUserPhysicalPages : 
        hProcess : IntPtr * 
        refNumberOfPages : IntPtr byref * 
        pageArray : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to a process. 

 The function frees memory within the virtual address space of this process.</dd><dt>refNumberOfPages</dt><dd>Type: System.IntPtr<br />The size of the physical memory to free, in pages. 

 On return, if the function fails, this parameter indicates the number of pages that are freed.</dd><dt>pageArray</dt><dd>Type: System.IntPtr<br />A pointer to an array of page frame numbers of the allocated memory to be freed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic), in this case, the *refNumberOfPages* parameter reflect how many pages have actually been released. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-freeuserphysicalpages" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-freeuserphysicalpages</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeUserPhysicalPages">FreeUserPhysicalPages Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />