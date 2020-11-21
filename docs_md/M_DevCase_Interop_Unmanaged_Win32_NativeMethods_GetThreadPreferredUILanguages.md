# NativeMethods.GetThreadPreferredUILanguages Method (MuiLanguageMode, UInt32, IntPtr, UInt32)
 

Retrieves the preferred UI languages for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static bool GetThreadPreferredUILanguages(
	MuiLanguageMode flags,
	out uint refNumLanguages,
	IntPtr languagesBuffer,
	ref uint refLanguagesBufferSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function GetThreadPreferredUILanguages ( 
	flags As MuiLanguageMode,
	<OutAttribute> ByRef refNumLanguages As UInteger,
	languagesBuffer As IntPtr,
	ByRef refLanguagesBufferSize As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As MuiLanguageMode
Dim refNumLanguages As UInteger
Dim languagesBuffer As IntPtr
Dim refLanguagesBufferSize As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetThreadPreferredUILanguages(flags, 
	refNumLanguages, languagesBuffer, 
	refLanguagesBufferSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static bool GetThreadPreferredUILanguages(
	MuiLanguageMode flags, 
	[OutAttribute] unsigned int% refNumLanguages, 
	IntPtr languagesBuffer, 
	unsigned int% refLanguagesBufferSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member GetThreadPreferredUILanguages : 
        flags : MuiLanguageMode * 
        refNumLanguages : uint32 byref * 
        languagesBuffer : IntPtr * 
        refLanguagesBufferSize : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MuiLanguageMode">DevCase.Interop.Unmanaged.Win32.Enums.MuiLanguageMode</a><br />Flags identifying the language format to use for the thread preferred UI languages.</dd><dt>refNumLanguages</dt><dd>Type: System.UInt32<br />Pointer to the number of languages retrieved in *languagesBuffer*.</dd><dt>languagesBuffer</dt><dd>Type: System.IntPtr<br />Optional. Pointer to a double null-terminated multi-string buffer in which the function retrieves an ordered, null-delimited list in preference order, starting with the most preferable. 

 Alternatively if this parameter is set to NULL and *languagesBuffer* is set to 0, the function retrieves the required size of the language buffer in *refLanguagesBufferSize*. 

 The required size includes the two null characters.</dd><dt>refLanguagesBufferSize</dt><dd>Type: System.UInt32<br />Pointer to the size, in characters, for the language buffer indicated by *languagesBuffer*. 

 On successful return from the function, the parameter contains the size of the retrieved language buffer. 

 Alternatively if this parameter is set to 0 and *languagesBuffer* is set to NULL, the function retrieves the required size of the language buffer in *refLanguagesBufferSize*.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getthreadpreferreduilanguages" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getthreadpreferreduilanguages</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetThreadPreferredUILanguages">GetThreadPreferredUILanguages Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />