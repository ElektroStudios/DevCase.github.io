# NativeMethods.RegisterApplicationRecoveryCallback Method 
 

Registers the active instance of an application for recovery.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult RegisterApplicationRecoveryCallback(
	Delegates.ApplicationRecoveryCallback recoveryCallback,
	IntPtr parameter,
	uint pingInterval,
	uint reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function RegisterApplicationRecoveryCallback ( 
	recoveryCallback As Delegates.ApplicationRecoveryCallback,
	parameter As IntPtr,
	pingInterval As UInteger,
	reserved As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim recoveryCallback As Delegates.ApplicationRecoveryCallback
Dim parameter As IntPtr
Dim pingInterval As UInteger
Dim reserved As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.RegisterApplicationRecoveryCallback(recoveryCallback, 
	parameter, pingInterval, reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult RegisterApplicationRecoveryCallback(
	Delegates.ApplicationRecoveryCallback^ recoveryCallback, 
	IntPtr parameter, 
	unsigned int pingInterval, 
	unsigned int reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member RegisterApplicationRecoveryCallback : 
        recoveryCallback : Delegates.ApplicationRecoveryCallback * 
        parameter : IntPtr * 
        pingInterval : uint32 * 
        reserved : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>recoveryCallback</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_ApplicationRecoveryCallback">DevCase.Interop.Unmanaged.Win32.Delegates.ApplicationRecoveryCallback</a><br />A pointer to the recovery callback function.</dd><dt>parameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable to be passed to the callback function. Can be NULL.</dd><dt>pingInterval</dt><dd>Type: System.UInt32<br />The recovery ping interval, in milliseconds. 

 By default, the interval is 5 seconds (RECOVERY_DEFAULT_PING_INTERVAL). 

 The maximum interval is 5 minutes. 

 If you specify zero, the default interval is used. 

 You must call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ApplicationRecoveryInProgress">ApplicationRecoveryInProgress(Boolean)</a> function within the specified interval to indicate to ARR that you are still actively recovering; otherwise, Windows Error Reporting (WER) terminates recovery. 

 Typically, you perform recovery in a loop with each iteration lasting no longer than the ping interval. Each iteration performs a block of recovery work followed by a call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ApplicationRecoveryInProgress">ApplicationRecoveryInProgress(Boolean)</a>. 

 Since you also use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ApplicationRecoveryInProgress">ApplicationRecoveryInProgress(Boolean)</a> to determine if the user wants to cancel recovery, you should consider a smaller interval, so you do not perform a lot of work unnecessarily.</dd><dt>reserved</dt><dd>Type: System.UInt32<br />Reserved for future use. Set to zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrecoverycallback" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-registerapplicationrecoverycallback</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />