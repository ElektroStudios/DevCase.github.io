# NativeMethods.UnregisterApplicationRecoveryCallback Method 
 

Removes the active instance of an application from the recovery list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult UnregisterApplicationRecoveryCallback()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function UnregisterApplicationRecoveryCallback As HResult
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As HResult

returnValue = NativeMethods.UnregisterApplicationRecoveryCallback()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult UnregisterApplicationRecoveryCallback()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member UnregisterApplicationRecoveryCallback : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on fail.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-unregisterapplicationrecoverycallback" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-unregisterapplicationrecoverycallback</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />