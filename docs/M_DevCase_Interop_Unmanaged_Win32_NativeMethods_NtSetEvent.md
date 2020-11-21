# NativeMethods.NtSetEvent Method 
 

Sets an event object to a Signaled state and attempts to satisfy as many waits as possible.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll")]
public static NTStatus NtSetEvent(
	IntPtr eventHandle,
	[OptionalAttribute] out int refPreviousState
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll">]
Public Shared Function NtSetEvent ( 
	eventHandle As IntPtr,
	<OptionalAttribute> <OutAttribute> ByRef refPreviousState As Integer
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim eventHandle As IntPtr
Dim refPreviousState As Integer
Dim returnValue As NTStatus

returnValue = NativeMethods.NtSetEvent(eventHandle, 
	refPreviousState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll")]
static NTStatus NtSetEvent(
	[InAttribute] IntPtr eventHandle, 
	[OptionalAttribute] [OutAttribute] int% refPreviousState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll")>]
static member NtSetEvent : 
        eventHandle : IntPtr * 
        [<OptionalAttribute>] refPreviousState : int byref -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>eventHandle</dt><dd>Type: System.IntPtr<br />A handle to an event object..</dd><dt>refPreviousState (Optional)</dt><dd>Type: System.Int32<br />An optional pointer to a variable where the previous state of the event object is stored on output. .</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://msdn.microsoft.com/en-us/windows/desktop/ff567092" target="_blank">https://msdn.microsoft.com/en-us/windows/desktop/ff567092</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />