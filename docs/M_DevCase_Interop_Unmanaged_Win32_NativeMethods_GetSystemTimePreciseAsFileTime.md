# NativeMethods.GetSystemTimePreciseAsFileTime Method (Int64)
 

Retrieves the current system date and time with the highest possible level of precision (<1us). 

 The retrieved information is in Coordinated Universal Time (UTC) format.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static void GetSystemTimePreciseAsFileTime(
	ref long refFiletime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Sub GetSystemTimePreciseAsFileTime ( 
	ByRef refFiletime As Long
)
```

**VB Usage**<br />
``` VB Usage
Dim refFiletime As Long

NativeMethods.GetSystemTimePreciseAsFileTime(refFiletime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static void GetSystemTimePreciseAsFileTime(
	long long% refFiletime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetSystemTimePreciseAsFileTime : 
        refFiletime : int64 byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refFiletime</dt><dd>Type: System.Int64<br />A pointer to a FILETIME structure that contains the current system date and time in UTC format.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtimepreciseasfiletime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemtimepreciseasfiletime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetSystemTimePreciseAsFileTime">GetSystemTimePreciseAsFileTime Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />