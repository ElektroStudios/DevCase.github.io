# NativeMethods.VirtualQuery Method (IntPtr, MemoryBasicInformation, IntPtr)
 

Retrieves information about a range of pages in the virtual address space of the calling (current) process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr VirtualQuery(
	IntPtr address,
	ref MemoryBasicInformation refBuffer,
	IntPtr length
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function VirtualQuery ( 
	address As IntPtr,
	ByRef refBuffer As MemoryBasicInformation,
	length As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim refBuffer As MemoryBasicInformation
Dim length As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.VirtualQuery(address, 
	refBuffer, length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr VirtualQuery(
	IntPtr address, 
	MemoryBasicInformation% refBuffer, 
	IntPtr length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member VirtualQuery : 
        address : IntPtr * 
        refBuffer : MemoryBasicInformation byref * 
        length : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />A pointer to the base address of the region of pages to be queried. This value is rounded down to the next page boundary. 

 To determine the size of a page on the host computer, use the `GetSystemInfo` function.</dd><dt>refBuffer</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">DevCase.Interop.Unmanaged.Win32.Structures.MemoryBasicInformation</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MemoryBasicInformation">MemoryBasicInformation</a> structure in which information about the specified page range is returned.</dd><dt>length</dt><dd>Type: System.IntPtr<br />The size of the buffer pointed to by the lpBuffer parameter, in bytes.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the actual number of bytes returned in the information buffer 

 If the function fails, the return value is 0. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa366902%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa366902%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_VirtualQuery">VirtualQuery Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />