# NativeMethods.HeapReAlloc Method 
 

Reallocates a block of memory from a heap. 

 This function enables you to resize a memory block and change other memory block properties. The allocated memory is not movable.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr HeapReAlloc(
	IntPtr hHeap,
	HeapFlags flags,
	IntPtr mem,
	uint bytes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapReAlloc ( 
	hHeap As IntPtr,
	flags As HeapFlags,
	mem As IntPtr,
	bytes As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim flags As HeapFlags
Dim mem As IntPtr
Dim bytes As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.HeapReAlloc(hHeap, 
	flags, mem, bytes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr HeapReAlloc(
	IntPtr hHeap, 
	HeapFlags flags, 
	IntPtr mem, 
	unsigned int bytes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapReAlloc : 
        hHeap : IntPtr * 
        flags : HeapFlags * 
        mem : IntPtr * 
        bytes : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap from which the memory is to be reallocated. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap reallocation options. 

 Specifying any of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">HeapFlags</a> values will override the corresponding value specified when the heap was created with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a>.</dd><dt>mem</dt><dd>Type: System.IntPtr<br />A pointer to the block of memory that the function reallocates. 

 This pointer is returned by an earlier call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32) function.</dd><dt>bytes</dt><dd>Type: System.UInt32<br />The new size of the memory block, in bytes. 

 A memory block's size can be increased or decreased by using this function. 

 If the heap specified by the *hHeap* parameter is a "non-growable" heap, *bytes* must be less than 0x7FFF8. 

 You create a non-growable heap by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> function passing a nonzero value to its `maximumSize` parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a pointer to the reallocated memory block. 

 If the function fails and you have not specified <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">GenerateExceptions</a>, the return value is Zero. 

 If the function fails and you have specified <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">GenerateExceptions</a>, the function may generate an exception. The particular exception depends upon the nature of the heap corruption.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapalloc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapalloc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />