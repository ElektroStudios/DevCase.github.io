# NativeMethods.GetSystemDefaultLocaleName Method 
 

Retrieves the system default locale name. 

 Note: it is recommended that applications call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetUserDefaultLocaleName">GetUserDefaultLocaleName(StringBuilder, Int32)</a> in preference over this function. This is due to the user locale generally being more useful and accurate for the user than the system locale.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static bool GetSystemDefaultLocaleName(
	StringBuilder localeName,
	int length
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function GetSystemDefaultLocaleName ( 
	localeName As StringBuilder,
	length As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim localeName As StringBuilder
Dim length As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.GetSystemDefaultLocaleName(localeName, 
	length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static bool GetSystemDefaultLocaleName(
	StringBuilder^ localeName, 
	int length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member GetSystemDefaultLocaleName : 
        localeName : StringBuilder * 
        length : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>localeName</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a buffer in which this function retrieves the locale name.</dd><dt>length</dt><dd>Type: System.Int32<br />Size, in characters, of the output buffer indicated by *localeName* parameter. 

 The maximum possible character length of a locale name (including a terminating null character) is the value of LOCALE_NAME_MAX_LENGTH. This is the recommended size.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlocalename" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getsystemdefaultlocalename</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />