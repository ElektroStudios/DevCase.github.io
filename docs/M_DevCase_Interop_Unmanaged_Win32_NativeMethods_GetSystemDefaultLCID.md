# NativeMethods.GetSystemDefaultLCID Method 
 

Returns the locale identifier for the system locale. 

 Note: any application that runs only on Windows Vista and later should use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetSystemDefaultLocaleName">GetSystemDefaultLocaleName(StringBuilder, Int32)</a> in preference to this function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static uint GetSystemDefaultLCID()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetSystemDefaultLCID As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetSystemDefaultLCID()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned int GetSystemDefaultLCID()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetSystemDefaultLCID : unit -> uint32 

```


#### Return Value
Type: UInt32<br />Returns the locale identifier for the system default locale.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlcid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlcid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />