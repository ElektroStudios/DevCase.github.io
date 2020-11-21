# NativeMethods.EnumUILanguages Method 
 

Enumerates the user interface languages that are available on the operating system and calls the callback function with every language in the list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumUILanguages(
	Delegates.EnumUILanguagesProc uiLanguageEnumProc,
	MuiLanguageMode flags,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumUILanguages ( 
	uiLanguageEnumProc As Delegates.EnumUILanguagesProc,
	flags As MuiLanguageMode,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim uiLanguageEnumProc As Delegates.EnumUILanguagesProc
Dim flags As MuiLanguageMode
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumUILanguages(uiLanguageEnumProc, 
	flags, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumUILanguages(
	Delegates.EnumUILanguagesProc^ uiLanguageEnumProc, 
	MuiLanguageMode flags, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumUILanguages : 
        uiLanguageEnumProc : Delegates.EnumUILanguagesProc * 
        flags : MuiLanguageMode * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>uiLanguageEnumProc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumUILanguagesProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumUILanguagesProc</a><br />Pointer to an application-defined <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumUILanguagesProc">Delegates.EnumUILanguagesProc</a> callback function. 

EnumUILanguages(Delegates.EnumUILanguagesProc, MuiLanguageMode, IntPtr) calls this callback function repeatedly to enumerate the languages in the list.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MuiLanguageMode">DevCase.Interop.Unmanaged.Win32.Enums.MuiLanguageMode</a><br />Flags identifying language format and filtering.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Application-defined value.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumuilanguagesa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumuilanguagesa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />