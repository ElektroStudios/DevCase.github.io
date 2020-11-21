# NativeMethods.NtFreezeRegistry Method 
 

Pauses registry data flushes for the specified time period. 

 The function uses a timer to automaticaly unblock the flushes, so there's no need to manually call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtThawRegistry">NtThawRegistry()</a>, unless you want to end the pause during the timeout period.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static NTStatus NtFreezeRegistry(
	ulong timeOutInSeconds
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtFreezeRegistry ( 
	timeOutInSeconds As ULong
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim timeOutInSeconds As ULong
Dim returnValue As NTStatus

returnValue = NativeMethods.NtFreezeRegistry(timeOutInSeconds)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static NTStatus NtFreezeRegistry(
	unsigned long long timeOutInSeconds
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtFreezeRegistry : 
        timeOutInSeconds : uint64 -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>timeOutInSeconds</dt><dd>Type: System.UInt64<br />Length of time, in seconds, to pause registry flushes. If set to 0, a default of 60 is used.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success.

## Remarks
<a href="http://undoc.airesoft.co.uk/ntdll.dll/NtFreezeRegistry.php" target="_blank">http://undoc.airesoft.co.uk/ntdll.dll/NtFreezeRegistry.php</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />