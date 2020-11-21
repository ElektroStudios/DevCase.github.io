# NativeMethods.HeapValidate Method 
 

Validates the specified heap. 

 The function scans all the memory blocks in the heap and verifies that the heap control structures maintained by the heap manager are in a consistent state. 

 You can also use the HeapValidate(IntPtr, HeapFlags, IntPtr) function to validate a single memory block within a specified heap without checking the validity of the entire heap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool HeapValidate(
	IntPtr hHeap,
	HeapFlags flags,
	IntPtr mem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function HeapValidate ( 
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

returnValue = NativeMethods.HeapValidate(hHeap, 
	flags, mem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool HeapValidate(
	[InAttribute] IntPtr hHeap, 
	HeapFlags flags, 
	[InAttribute] IntPtr mem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member HeapValidate : 
        hHeap : IntPtr * 
        flags : HeapFlags * 
        mem : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap to be validated. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HeapFlags">DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags</a><br />The heap access options.</dd><dt>mem</dt><dd>Type: System.IntPtr<br />A pointer to a memory block within the specified heap. This parameter may be Zero. 

 If this parameter is Zero, the function attempts to validate the entire heap specified by *hHeap*. 

 If this parameter is not Zero, the function attempts to validate the memory block pointed to by *mem*. It does not attempt to validate the rest of the heap.</dd></dl>

#### Return Value
Type: Boolean<br />If the specified heap or memory block is valid, the return value is `true` (`True` in Visual Basic). 

 If the specified heap or memory block is invalid, the return value is `false` (`False` in Visual Basic). 

 On a system set up for debugging, the HeapValidate(IntPtr, HeapFlags, IntPtr) function then displays debugging messages that describe the part of the heap or memory block that is invalid, and stops at a hard-coded breakpoint so that you can examine the system to determine the source of the invalidity. 

 The HeapValidate(IntPtr, HeapFlags, IntPtr) function does not set the thread's last error value. 

 There is no extended error information for this function; do not call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapvalidate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heapvalidate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />