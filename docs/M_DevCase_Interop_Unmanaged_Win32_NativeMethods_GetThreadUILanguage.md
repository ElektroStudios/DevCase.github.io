# NativeMethods.GetThreadUILanguage Method 
 

Returns the language identifier of the first user interface language for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ushort GetThreadUILanguage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetThreadUILanguage As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetThreadUILanguage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned short GetThreadUILanguage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetThreadUILanguage : unit -> uint16 

```


#### Return Value
Type: UInt16<br />Returns the identifier for a language explicitly associated with the thread by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetThreadUILanguage">SetThreadUILanguage(UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetThreadPreferredUILanguages">SetThreadPreferredUILanguages(MuiLanguageMode, String, UInt32)</a>. 

 Alternatively, if no language has been explicitly associated with the current thread, the identifier can indicate a user or system user interface language.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getthreaduilanguage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getthreaduilanguage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />