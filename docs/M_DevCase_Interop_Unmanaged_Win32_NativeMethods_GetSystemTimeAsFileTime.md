# NativeMethods.GetSystemTimeAsFileTime Method 
 

Retrieves the current system date and time. The information is in Coordinated Universal Time (UTC) format.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void GetSystemTimeAsFileTime(
	out FILETIME refSystemTimeAsFileTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub GetSystemTimeAsFileTime ( 
	<OutAttribute> ByRef refSystemTimeAsFileTime As FILETIME
)
```

**VB Usage**<br />
``` VB Usage
Dim refSystemTimeAsFileTime As FILETIMENativeMethods.GetSystemTimeAsFileTime(refSystemTimeAsFileTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void GetSystemTimeAsFileTime(
	[OutAttribute] FILETIME% refSystemTimeAsFileTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetSystemTimeAsFileTime : 
        refSystemTimeAsFileTime : FILETIME byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refSystemTimeAsFileTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure to receive the current system date and time in UTC format.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtimeasfiletime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtimeasfiletime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />