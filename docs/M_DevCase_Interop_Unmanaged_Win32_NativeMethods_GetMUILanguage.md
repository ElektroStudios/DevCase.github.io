# NativeMethods.GetMUILanguage Method 
 

Gets the language currently in use by the common controls for a particular process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", ExactSpelling = true)]
public static ushort GetMUILanguage()
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", ExactSpelling := true>]
Public Shared Function GetMUILanguage As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetMUILanguage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", ExactSpelling = true)]
static unsigned short GetMUILanguage()
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", ExactSpelling = true)>]
static member GetMUILanguage : unit -> uint16 

```


#### Return Value
Type: UInt16<br />Returns the language identifier of the language an application has specified for the common controls by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InitMUILanguage">InitMUILanguage(UInt16)</a>. 

GetMUILanguage() returns the value for the process from which it is called. If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_InitMUILanguage">InitMUILanguage(UInt16)</a> has not been called or was not called from the same process, GetMUILanguage() returns the language-neutral LANGID, `MAKELANGID`(LANG_NEUTRAL, SUBLANG_NEUTRAL).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-getmuilanguage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-getmuilanguage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />