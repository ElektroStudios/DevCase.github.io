# NativeMethods.HeapFree Method 
 

Frees a memory block allocated from a heap by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapReAlloc">HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool HeapFree(
	IntPtr hHeap,
	HeapFlags flags,
	IntPtr mem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapFree ( 
	hHeap As IntPtr,
	flags As HeapFlags,
	mem As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim flags As HeapFlags
Dim mem As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.HeapFree(hHeap, 
	flags, mem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool HeapFree(
	IntPtr hHeap, 
	HeapFlags flags, 
	IntPtr mem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapFree : 
        hHeap : IntPtr * 
        flags : HeapFlags * 
        mem : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap whose memory block is to be freed. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap free options. 

 Specifying a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">HeapFlags</a> value overrides the corresponding value specified in the `options` parameter when the heap was created by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> function: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">NoSerialize</a></dd><dt>mem</dt><dd>Type: System.IntPtr<br />A pointer to the memory block to be freed. 

 This pointer is returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapAlloc">HeapAlloc(IntPtr, HeapFlags, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapReAlloc">HeapReAlloc(IntPtr, HeapFlags, IntPtr, UInt32)</a> function. 

 If this pointer is Zero, the behavior is undefined.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapfree" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapfree</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />