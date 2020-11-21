# NativeMethods.CoWaitForMultipleHandles Method 
 

Waits for specified handles to be signaled or for a specified timeout period to elapse.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", SetLastError = true)]
public static HResult CoWaitForMultipleHandles(
	CoWaitForMultipleHandlesFlags flags,
	uint signalTimeout,
	uint handleCount,
	IntPtr[] handles,
	ref uint refHandleIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", SetLastError := true>]
Public Shared Function CoWaitForMultipleHandles ( 
	flags As CoWaitForMultipleHandlesFlags,
	signalTimeout As UInteger,
	handleCount As UInteger,
	handles As IntPtr(),
	ByRef refHandleIndex As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim flags As CoWaitForMultipleHandlesFlags
Dim signalTimeout As UInteger
Dim handleCount As UInteger
Dim handles As IntPtr()
Dim refHandleIndex As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.CoWaitForMultipleHandles(flags, 
	signalTimeout, handleCount, handles, 
	refHandleIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", SetLastError = true)]
static HResult CoWaitForMultipleHandles(
	CoWaitForMultipleHandlesFlags flags, 
	unsigned int signalTimeout, 
	unsigned int handleCount, 
	array<IntPtr>^ handles, 
	unsigned int% refHandleIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", SetLastError = true)>]
static member CoWaitForMultipleHandles : 
        flags : CoWaitForMultipleHandlesFlags * 
        signalTimeout : uint32 * 
        handleCount : uint32 * 
        handles : IntPtr[] * 
        refHandleIndex : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CoWaitForMultipleHandlesFlags">DevCase.Interop.Unmanaged.Win32.Enums.CoWaitForMultipleHandlesFlags</a><br />The handle wait options.</dd><dt>signalTimeout</dt><dd>Type: System.UInt32<br />The timeout period, in milliseconds.</dd><dt>handleCount</dt><dd>Type: System.UInt32<br />The number of elements in the pHandles array.</dd><dt>handles</dt><dd>Type: System.IntPtr[]<br />An array of handles.</dd><dt>refHandleIndex</dt><dd>Type: System.UInt32<br />A pointer to a variable that, when the returned status is S_OK, receives a value indicating the event that caused the function to return. 

 This value is usually the index into *handles* for the handle that was signaled. 

 If *handles* includes one or more handles to mutex objects, a value between WAIT_ABANDONED_0 and (WAIT_ABANDONED_0 + nCount 1) indicates the index into *handles* for the mutex that was abandoned. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CoWaitForMultipleHandlesFlags">Alertable</a> flag is set in *flags*, a value of WAIT_IO_COMPLETION indicates the wait was ended by one or more user-mode asynchronous procedure calls (APC) queued to the thread.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs. 

 Note that the return value of CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32) can be nondeterministic if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CoWaitForMultipleHandlesFlags">Alertable</a> flag is set in *flags*, or if *handles* includes one or more handles to mutex objects. 

 The recommended workaround is to call SetLastError(ERROR_SUCCESS) before CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags, UInt32, UInt32, IntPtr[], UInt32).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cowaitformultiplehandles" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-cowaitformultiplehandles</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mre As New ManualResetEvent(initialState:=False)
Dim waitHandles As IntPtr() = {mre.SafeWaitHandle.DangerousGetHandle()}
Dim handleLength As UInteger = CUInt(waitHandles.Length)
Dim handleIndex As UInteger
Dim signalTimeout As UInteger = 0UI

Do While True
    ' Intensive work here...

   Dim result As HResult = NativeMethods.CoWaitForMultipleHandles(CoWaitForMultipleHandlesFlags.Default, signalTimeout, handleLength, waitHandles, handleIndex)
Loop

mre.Dispose()
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />