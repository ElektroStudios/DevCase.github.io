# NativeMethods.FileTimeToSystemTime Method 
 

Converts a file time to system time format. System time is based on Coordinated Universal Time (UTC).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool FileTimeToSystemTime(
	ref FILETIME refFileTime,
	out SystemTime refSystemTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function FileTimeToSystemTime ( 
	ByRef refFileTime As FILETIME,
	<OutAttribute> ByRef refSystemTime As SystemTime
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refFileTime As FILETIME
Dim refSystemTime As SystemTime
Dim returnValue As Boolean

returnValue = NativeMethods.FileTimeToSystemTime(refFileTime, 
	refSystemTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool FileTimeToSystemTime(
	FILETIME% refFileTime, 
	[OutAttribute] SystemTime% refSystemTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member FileTimeToSystemTime : 
        refFileTime : FILETIME byref * 
        refSystemTime : SystemTime byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refFileTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure containing the file time to be converted to system (UTC) date and time format. 

 This value must be less than `0x8000000000000000`. Otherwise, the function fails.</dd><dt>refSystemTime</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">DevCase.Interop.Unmanaged.Win32.Structures.SystemTime</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">SystemTime</a> structure to receive the converted file time.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/timezoneapi/nf-timezoneapi-filetimetosystemtime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/timezoneapi/nf-timezoneapi-filetimetosystemtime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />