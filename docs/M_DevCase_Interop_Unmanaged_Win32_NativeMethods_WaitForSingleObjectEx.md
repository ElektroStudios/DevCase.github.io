# NativeMethods.WaitForSingleObjectEx Method 
 

Waits until the specified object is in the signaled state, an I/O completion routine or asynchronous procedure call (APC) is queued to the thread, or the time-out interval elapses.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static WaitObjectResult WaitForSingleObjectEx(
	IntPtr handle,
	uint milliseconds,
	bool alertable
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function WaitForSingleObjectEx ( 
	handle As IntPtr,
	milliseconds As UInteger,
	alertable As Boolean
) As WaitObjectResult
```

**VB Usage**<br />
``` VB Usage
Dim handle As IntPtr
Dim milliseconds As UInteger
Dim alertable As Boolean
Dim returnValue As WaitObjectResult

returnValue = NativeMethods.WaitForSingleObjectEx(handle, 
	milliseconds, alertable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static WaitObjectResult WaitForSingleObjectEx(
	IntPtr handle, 
	unsigned int milliseconds, 
	bool alertable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member WaitForSingleObjectEx : 
        handle : IntPtr * 
        milliseconds : uint32 * 
        alertable : bool -> WaitObjectResult 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: System.IntPtr<br />A handle to the object. 

 If this handle is closed while the wait is still pending, the function's behavior is undefined. 

 The handle must have the `SYNCHRONIZE` access right.</dd><dt>milliseconds</dt><dd>Type: System.UInt32<br />The time-out interval, in milliseconds. 

 If a nonzero value is specified, the function waits until the object is signaled, an I/O completion routine or APC is queued, or the interval elapses. 

 If *milliseconds* is zero, the function does not enter a wait state if the criteria is not met; it always returns immediately. 

 If *milliseconds* is INFINITE (`0xFFFFFFFF`), the function will return only when the object is signaled or an I/O completion routine or APC is queued</dd><dt>alertable</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic) and the thread is in the waiting state, the function returns when the system queues an I/O completion routine or APC, and the thread runs the routine or function. 

 Otherwise, the function does not return, and the completion routine or APC function is not executed. 

 A completion routine is queued when the `ReadFileEx` or `WriteFileEx` function in which it was specified has completed. 

 The wait function returns and the completion routine is called only if bAlertable is `true` (`True` in Visual Basic), and the calling thread is the thread that initiated the read or write operation. An APC is queued when you call `QueueUserAPC`.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WaitObjectResult">WaitObjectResult</a><br />If the function succeeds, the return value indicates the event that caused the function to return.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms687036(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms687036(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />