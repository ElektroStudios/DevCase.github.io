# NativeMethods.GetApplicationRecoveryCallback Method 
 

Retrieves a pointer to the callback routine registered for the specified process. 

 The address returned is in the virtual address space of the process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult GetApplicationRecoveryCallback(
	IntPtr hProcess,
	out Delegates.ApplicationRecoveryCallback refRecoveryCallback,
	out IntPtr refParameter,
	out uint refPingInterval,
	out int refReserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetApplicationRecoveryCallback ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refRecoveryCallback As Delegates.ApplicationRecoveryCallback,
	<OutAttribute> ByRef refParameter As IntPtr,
	<OutAttribute> ByRef refPingInterval As UInteger,
	<OutAttribute> ByRef refReserved As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refRecoveryCallback As Delegates.ApplicationRecoveryCallback
Dim refParameter As IntPtr
Dim refPingInterval As UInteger
Dim refReserved As Integer
Dim returnValue As HResult

returnValue = NativeMethods.GetApplicationRecoveryCallback(hProcess, 
	refRecoveryCallback, refParameter, 
	refPingInterval, refReserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult GetApplicationRecoveryCallback(
	IntPtr hProcess, 
	[OutAttribute] Delegates.ApplicationRecoveryCallback^% refRecoveryCallback, 
	[OutAttribute] IntPtr% refParameter, 
	[OutAttribute] unsigned int% refPingInterval, 
	[OutAttribute] int% refReserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetApplicationRecoveryCallback : 
        hProcess : IntPtr * 
        refRecoveryCallback : Delegates.ApplicationRecoveryCallback byref * 
        refParameter : IntPtr byref * 
        refPingInterval : uint32 byref * 
        refReserved : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. This handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access right.</dd><dt>refRecoveryCallback</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_ApplicationRecoveryCallback">DevCase.Interop.Unmanaged.Win32.Delegates.ApplicationRecoveryCallback</a><br />A pointer to the recovery callback function. For more information, see ApplicationRecoveryCallback.</dd><dt>refParameter</dt><dd>Type: System.IntPtr<br />A pointer to the callback parameter.</dd><dt>refPingInterval</dt><dd>Type: System.UInt32<br />The recovery ping interval, in 100-nanosecond intervals.</dd><dt>refReserved</dt><dd>Type: System.Int32<br />Reserved for future use.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getapplicationrecoverycallback" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-getapplicationrecoverycallback</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />