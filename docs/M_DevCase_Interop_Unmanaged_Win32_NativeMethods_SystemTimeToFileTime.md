# NativeMethods.SystemTimeToFileTime Method 
 

Converts a system time to file time format. System time is based on Coordinated Universal Time (UTC).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SystemTimeToFileTime(
	ref SystemTime refSystemTime,
	out FILETIME refFileTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SystemTimeToFileTime ( 
	ByRef refSystemTime As SystemTime,
	<OutAttribute> ByRef refFileTime As FILETIME
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refSystemTime As SystemTime
Dim refFileTime As FILETIME
Dim returnValue As Boolean

returnValue = NativeMethods.SystemTimeToFileTime(refSystemTime, 
	refFileTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SystemTimeToFileTime(
	SystemTime% refSystemTime, 
	[OutAttribute] FILETIME% refFileTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SystemTimeToFileTime : 
        refSystemTime : SystemTime byref * 
        refFileTime : FILETIME byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refSystemTime</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">DevCase.Interop.Unmanaged.Win32.Structures.SystemTime</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">SystemTime</a> structure that contains the system time to be converted from UTC to file time format. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime_DayOfWeek">DayOfWeek</a> member is ignored.</dd><dt>refFileTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure to receive the converted system time.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/timezoneapi/nf-timezoneapi-systemtimetofiletime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/timezoneapi/nf-timezoneapi-systemtimetofiletime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />