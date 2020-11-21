# NativeMethods.GetLocalTime Method 
 

Retrieves the current local date and time. 

 To retrieve the current date and time in Coordinated Universal Time (UTC) format, use the GetLocalTime(SystemTime) function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static void GetLocalTime(
	ref SystemTime refTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Sub GetLocalTime ( 
	ByRef refTime As SystemTime
)
```

**VB Usage**<br />
``` VB Usage
Dim refTime As SystemTimeNativeMethods.GetLocalTime(refTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static void GetLocalTime(
	SystemTime% refTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetLocalTime : 
        refTime : SystemTime byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refTime</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">DevCase.Interop.Unmanaged.Win32.Structures.SystemTime</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SystemTime">SystemTime</a> structure that receives the current local date and time.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getlocaltime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getlocaltime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />