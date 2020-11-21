# NativeMethods.GetUserDefaultLCID Method 
 

Returns the locale identifier for the user default locale. 

 Caution: If the user default locale is a custom locale, an application cannot accurately tag data with the value or exchange it. In this case, the application should use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetUserDefaultLocaleName">GetUserDefaultLocaleName(StringBuilder, Int32)</a> in preference to GetUserDefaultLCID(). 

 Note: applications that are intended to run only on Windows Vista and later should use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetUserDefaultLocaleName">GetUserDefaultLocaleName(StringBuilder, Int32)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static uint GetUserDefaultLCID()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetUserDefaultLCID As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UInteger

returnValue = NativeMethods.GetUserDefaultLCID()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned int GetUserDefaultLCID()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetUserDefaultLCID : unit -> uint32 

```


#### Return Value
Type: UInt32<br />Returns the locale identifier for the user default locale.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultlcid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultlcid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />