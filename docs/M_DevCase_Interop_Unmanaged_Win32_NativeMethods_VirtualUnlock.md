# NativeMethods.VirtualUnlock Method (IntPtr, IntPtr)
 

Locks the specified region of the process's virtual address space into physical memory, ensuring that subsequent access to the region will not incur a page fault.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool VirtualUnlock(
	IntPtr address,
	IntPtr size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function VirtualUnlock ( 
	address As IntPtr,
	size As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.VirtualUnlock(address, 
	size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool VirtualUnlock(
	IntPtr address, 
	IntPtr size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member VirtualUnlock : 
        address : IntPtr * 
        size : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />A pointer to the base address of the region of pages to be unlocked.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The size of the region being unlocked, in bytes. 

 The region of affected pages includes all pages that contain one or more bytes in the range from the *address* parameter to (*address*+*size*). This means that a 2-byte range straddling a page boundary causes both pages to be unlocked.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualunlock" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/memoryapi/nf-memoryapi-virtualunlock</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualUnlock">VirtualUnlock Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />