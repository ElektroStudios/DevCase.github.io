# NativeMethods.HeapLock Method 
 

Attempts to acquire the critical section object, or lock, that is associated with a specified heap.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool HeapLock(
	IntPtr hHeap
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function HeapLock ( 
	hHeap As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hHeap As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.HeapLock(hHeap)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool HeapLock(
	[InAttribute] IntPtr hHeap
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member HeapLock : 
        hHeap : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hHeap</dt><dd>Type: System.IntPtr<br />A handle to the heap to be locked. 

 This handle is returned by either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessHeap">GetProcessHeap()</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heaplock" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/heapapi/nf-heapapi-heaplock</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />