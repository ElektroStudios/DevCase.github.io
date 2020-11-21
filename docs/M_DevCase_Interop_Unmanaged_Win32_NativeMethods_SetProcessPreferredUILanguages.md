# NativeMethods.SetProcessPreferredUILanguages Method 
 

Sets the process preferred UI languages for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static bool SetProcessPreferredUILanguages(
	MuiLanguageMode flags,
	string languagesBuffer,
	out uint refNumLanguages
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function SetProcessPreferredUILanguages ( 
	flags As MuiLanguageMode,
	languagesBuffer As String,
	<OutAttribute> ByRef refNumLanguages As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As MuiLanguageMode
Dim languagesBuffer As String
Dim refNumLanguages As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessPreferredUILanguages(flags, 
	languagesBuffer, refNumLanguages)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static bool SetProcessPreferredUILanguages(
	MuiLanguageMode flags, 
	String^ languagesBuffer, 
	[OutAttribute] unsigned int% refNumLanguages
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member SetProcessPreferredUILanguages : 
        flags : MuiLanguageMode * 
        languagesBuffer : string * 
        refNumLanguages : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MuiLanguageMode">DevCase.Interop.Unmanaged.Win32.Enums.MuiLanguageMode</a><br />Flags identifying the language format to use for the process preferred UI languages.</dd><dt>languagesBuffer</dt><dd>Type: System.String<br />Pointer to a double null-terminated multi-string buffer that contains an ordered, null-delimited list in decreasing order of preference. 

 If there are more than five languages in the buffer, the function only sets the first five valid languages. 

 Alternatively, this parameter can contain NULL if no language list is required. In this case, the function clears the preferred UI languages for the process.</dd><dt>refNumLanguages</dt><dd>Type: System.UInt32<br />Pointer to the number of languages that has been set in the process language list from the input buffer, up to a maximum of five.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-setprocesspreferreduilanguages" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-setprocesspreferreduilanguages</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />