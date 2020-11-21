# Delegates.EnumUILanguagesProc Delegate
 

An application-defined callback function that processes enumerated user interface language information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumUILanguages">EnumUILanguages(Delegates.EnumUILanguagesProc, MuiLanguageMode, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumUILanguagesProc(
	string uiLanguageString,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function EnumUILanguagesProc ( 
	uiLanguageString As String,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumUILanguagesProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumUILanguagesProc(
	String^ uiLanguageString, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
type EnumUILanguagesProc = 
    delegate of 
        uiLanguageString : string * 
        lParam : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>uiLanguageString</dt><dd>Type: System.String<br />Pointer to a buffer containing a null-terminated string representing a user interface language identifier or language name, depending on the value for the `flags` parameter passed in the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumUILanguages">EnumUILanguages(Delegates.EnumUILanguagesProc, MuiLanguageMode, IntPtr)</a>.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />Application-defined value.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) to continue enumeration or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumuilanguagesw" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-enumuilanguagesw</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />