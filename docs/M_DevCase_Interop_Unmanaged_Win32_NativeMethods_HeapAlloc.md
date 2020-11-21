# NativeMethods.HeapAlloc Method 
 

Allocates a block of memory from a heap. The allocated memory is not movable.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static IntPtr HeapAlloc(
	IntPtr hHeap,
	HeapFlags flags,
	uint bytes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function HeapAlloc ( 
	hHeap As IntPtr,
	flags As HeapFlags,
	bytes As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim flags As HeapFlags
Dim bytes As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.HeapAlloc(hHeap, 
	flags, bytes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static IntPtr HeapAlloc(
	IntPtr hHeap, 
	HeapFlags flags, 
	unsigned int bytes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member HeapAlloc : 
        hHeap : IntPtr * 
        flags : HeapFlags * 
        bytes : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap from which the memory will be allocated. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap allocation options. 

 Specifying any of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">HeapFlags</a> values will override the corresponding value specified when the heap was created with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a>.</dd><dt>bytes</dt><dd>Type: System.UInt32<br />The number of bytes to be allocated. 

 If the heap specified by the hHeap parameter is a "non-growable" heap, *bytes* parameter must be less than 0x7FFF8. 

 You create a non-growable heap by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> function passing a nonzero value to its `maximumSize` parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a pointer to the allocated memory block. 

 If the function fails and you have not specified <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">GenerateExceptions</a>, the return value is Zero. 

 If the function fails and you have specified <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">GenerateExceptions</a>, the function may generate an exception. The particular exception depends upon the nature of the heap corruption. 

 If the function fails, it does not call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLastError">SetLastError(Win32ErrorCode)</a>. An application cannot call GetLastWin32Error() for extended error information.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapalloc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapalloc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />