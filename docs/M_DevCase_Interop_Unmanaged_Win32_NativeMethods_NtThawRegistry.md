# NativeMethods.NtThawRegistry Method 
 

Cancels any registry thawing and restores normal data flushing. 

 To pause registry data flushes for a specified time period, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtFreezeRegistry">NtFreezeRegistry(UInt64)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static NTStatus NtThawRegistry()
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtThawRegistry As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As NTStatus

returnValue = NativeMethods.NtThawRegistry()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static NTStatus NtThawRegistry()
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtThawRegistry : unit -> NTStatus 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success.

## Remarks
<a href="http://undoc.airesoft.co.uk/ntdll.dll/NtThawRegistry.php" target="_blank">http://undoc.airesoft.co.uk/ntdll.dll/NtThawRegistry.php</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />