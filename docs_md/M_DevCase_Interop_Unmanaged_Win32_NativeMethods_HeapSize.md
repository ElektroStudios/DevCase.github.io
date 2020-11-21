# NativeMethods.HeapSize Method 
 

Retrieves the size of a memory block allocated from a heap by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapReAlloc">HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static int HeapSize(
	IntPtr hHeap,
	HeapFlags flags,
	IntPtr mem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapSize ( 
	hHeap As IntPtr,
	flags As HeapFlags,
	mem As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim flags As HeapFlags
Dim mem As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.HeapSize(hHeap, 
	flags, mem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static int HeapSize(
	IntPtr hHeap, 
	HeapFlags flags, 
	IntPtr mem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapSize : 
        hHeap : IntPtr * 
        flags : HeapFlags * 
        mem : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap in which the memory block resides. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap size options. 

 Specifying a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">HeapFlags</a> value overrides the corresponding value specified in the `options` parameter when the heap was created by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> function.</dd><dt>mem</dt><dd>Type: System.IntPtr<br />A pointer to the memory block whose size the function will obtain. 

 This is a pointer returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapReAlloc">HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32)</a> function. 

 The memory block must be from the heap specified by the *hHeap* parameter.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is the requested size of the allocated memory block, in bytes. 

 If the function fails, the return value is (SIZE_T)-1. 

 The function does not call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLastError">SetLastError(Win32ErrorCode)</a>. An application cannot call GetLastWin32Error() for extended error information. 

 If the *mem* parameter refers to a heap allocation that is not in the heap specified by the *hHeap* parameter, the behavior of the HeapSize(IntPtr, HeapFlags, IntPtr) function is undefined.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapsize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapsize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />