# NativeMethods.SetSystemTime Method 
 

Sets the current system time and date. The system time is expressed in Coordinated Universal Time (UTC). 

 To set the local date and time, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLocalTime">SetLocalTime(SystemTime)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool SetSystemTime(
	ref SystemTime refTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetSystemTime ( 
	ByRef refTime As SystemTime
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refTime As SystemTime
Dim returnValue As Boolean

returnValue = NativeMethods.SetSystemTime(refTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool SetSystemTime(
	SystemTime% refTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetSystemTime : 
        refTime : SystemTime byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refTime</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">DevCase.Interop.Unmanaged.Win32.Structures.SystemTime</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">SystemTime</a> structure that contains the new system date and time. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime_DayOfWeek">DayOfWeek</a> member is ignored.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-setsystemtime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-setsystemtime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />