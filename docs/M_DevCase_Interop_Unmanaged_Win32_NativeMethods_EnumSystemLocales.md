# NativeMethods.EnumSystemLocales Method 
 

Enumerates the locales that are either installed on or supported by an operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumSystemLocales(
	Delegates.EnumLocalesProc localeEnumProc,
	EnumSystemLocalesFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumSystemLocales ( 
	localeEnumProc As Delegates.EnumLocalesProc,
	flags As EnumSystemLocalesFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim localeEnumProc As Delegates.EnumLocalesProc
Dim flags As EnumSystemLocalesFlags
Dim returnValue As Boolean

returnValue = NativeMethods.EnumSystemLocales(localeEnumProc, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumSystemLocales(
	Delegates.EnumLocalesProc^ localeEnumProc, 
	EnumSystemLocalesFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumSystemLocales : 
        localeEnumProc : Delegates.EnumLocalesProc * 
        flags : EnumSystemLocalesFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>localeEnumProc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumLocalesProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumLocalesProc</a><br />Pointer to an application-defined callback function. 

 The EnumSystemLocales(Delegates.EnumLocalesProc, EnumSystemLocalesFlags) function enumerates system locales by making repeated calls to this callback function. 

 For more information, see <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumLocalesProc">Delegates.EnumLocalesProc</a>.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EnumSystemLocalesFlags">DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemLocalesFlags</a><br />Flags specifying the locale identifiers to enumerate.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumsystemlocalesa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumsystemlocalesa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />