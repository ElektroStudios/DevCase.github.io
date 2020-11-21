# NativeMethods.GetSystemTime Method 
 

Retrieves the current system date and time. The system time is expressed in Coordinated Universal Time (UTC). 

 To retrieve the current system date and time in local time, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetLocalTime">GetLocalTime(SystemTime)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static void GetSystemTime(
	ref SystemTime refTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Sub GetSystemTime ( 
	ByRef refTime As SystemTime
)
```

**VB Usage**<br />
``` VB Usage
Dim refTime As SystemTimeNativeMethods.GetSystemTime(refTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static void GetSystemTime(
	SystemTime% refTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetSystemTime : 
        refTime : SystemTime byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refTime</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">DevCase.Interop.Unmanaged.Win32.Structures.SystemTime</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">SystemTime</a> structure that receives the current system date and time.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />