# NativeMethods.GetUserDefaultUILanguage Method 
 

Returns the language identifier for the user UI language for the current user. 

 If the current user has not set a language, GetUserDefaultUILanguage() returns the preferred language set for the system. 

 If there is no preferred language set for the system, then the system default UI language (also known as "install language") is returned.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ushort GetUserDefaultUILanguage()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetUserDefaultUILanguage As UShort
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As UShort

returnValue = NativeMethods.GetUserDefaultUILanguage()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static unsigned short GetUserDefaultUILanguage()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetUserDefaultUILanguage : unit -> uint16 

```


#### Return Value
Type: UInt16<br />Returns the language identifier for the user UI language for the current user.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultuilanguage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultuilanguage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />