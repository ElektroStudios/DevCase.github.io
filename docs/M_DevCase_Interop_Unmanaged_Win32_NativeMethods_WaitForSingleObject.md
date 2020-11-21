# NativeMethods.WaitForSingleObject Method 
 

Waits until the specified object is in the signaled state or the time-out interval elapses. 

 To enter an alertable wait state, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaitForSingleObjectEx">WaitForSingleObjectEx(IntPtr, UInt32, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static WaitObjectResult WaitForSingleObject(
	IntPtr handle,
	uint milliseconds
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function WaitForSingleObject ( 
	handle As IntPtr,
	milliseconds As UInteger
) As WaitObjectResult
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim milliseconds As UInteger
Dim returnValue As WaitObjectResult

returnValue = NativeMethods.WaitForSingleObject(handle, 
	milliseconds)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static WaitObjectResult WaitForSingleObject(
	IntPtr handle, 
	unsigned int milliseconds
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member WaitForSingleObject : 
        handle : IntPtr * 
        milliseconds : uint32 -> WaitObjectResult 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to the object. 

 If this handle is closed while the wait is still pending, the function's behavior is undefined. 

 The handle must have the `SYNCHRONIZE` access right.</dd><dt>milliseconds</dt><dd>Type: System.UInt32<br />The time-out interval, in milliseconds. 

 If a nonzero value is specified, the function waits until the object is signaled or the interval elapses. 

 If dwMilliseconds is zero, the function does not enter a wait state if the object is not signaled; it always returns immediately. 

 If *milliseconds* is INFINITE (`0xFFFFFFFF`), the function will return only when the object is signaled.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WaitObjectResult">WaitObjectResult</a><br />If the function succeeds, the return value indicates the event that caused the function to return.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms687032(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms687032(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />