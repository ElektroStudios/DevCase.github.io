# NativeMethods.InitMUILanguage Method 
 

Enables an application to specify a language to be used with the common controls that is different from the system language.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", ExactSpelling = true, SetLastError = true)]
public static void InitMUILanguage(
	ushort uiLang
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Sub InitMUILanguage ( 
	uiLang As UShort
)
```

**VB Usage**<br />
``` VB Usage
Dim uiLang As UShort

NativeMethods.InitMUILanguage(uiLang)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", ExactSpelling = true, SetLastError = true)]
static void InitMUILanguage(
	unsigned short uiLang
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", ExactSpelling = true, SetLastError = true)>]
static member InitMUILanguage : 
        uiLang : uint16 -> unit 

```


#### Parameters
&nbsp;<dl><dt>uiLang</dt><dd>Type: System.UInt16<br />The language identifier of the language to be used by the common controls.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-initmuilanguage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-initmuilanguage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />