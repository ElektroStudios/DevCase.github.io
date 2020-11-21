# NativeMethods.HeapCompact Method 
 

Returns the size of the largest committed free block in the specified heap. 

 If the Disable heap coalesce on free global flag is set, this function also coalesces adjacent free blocks of memory in the heap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static uint HeapCompact(
	IntPtr hHeap,
	HeapFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapCompact ( 
	hHeap As IntPtr,
	flags As HeapFlags
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim flags As HeapFlags
Dim returnValue As UInteger

returnValue = NativeMethods.HeapCompact(hHeap, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static unsigned int HeapCompact(
	[InAttribute] IntPtr hHeap, 
	HeapFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapCompact : 
        hHeap : IntPtr * 
        flags : HeapFlags -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap access options.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the size of the largest committed free block in the heap, in bytes. 

 If the function fails, the return value is zero. 

 In the unlikely case that there is absolutely no space available in the heap, the function return value is zero, and GetLastWin32Error() returns zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapcompact" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapcompact</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />