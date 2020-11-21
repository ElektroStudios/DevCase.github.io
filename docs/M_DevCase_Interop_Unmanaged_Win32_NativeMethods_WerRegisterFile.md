# NativeMethods.WerRegisterFile Method 
 

Registers a file to be collected when WER creates an error report.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerRegisterFile(
	string file,
	WerRegisterFileType regFileType,
	WerRegisterFileTypeFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerRegisterFile ( 
	file As String,
	regFileType As WerRegisterFileType,
	flags As WerRegisterFileTypeFlags
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim regFileType As WerRegisterFileType
Dim flags As WerRegisterFileTypeFlags
Dim returnValue As HResult

returnValue = NativeMethods.WerRegisterFile(file, 
	regFileType, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerRegisterFile(
	String^ file, 
	WerRegisterFileType regFileType, 
	WerRegisterFileTypeFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerRegisterFile : 
        file : string * 
        regFileType : WerRegisterFileType * 
        flags : WerRegisterFileTypeFlags -> HResult 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />The full path to the file. The maximum length of this path is MAX_PATH characters.</dd><dt>regFileType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WerRegisterFileType">DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileType</a><br />The file type.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WerRegisterFileTypeFlags">DevCase.Interop.Unmanaged.Win32.Enums.WerRegisterFileTypeFlags</a><br />Flags.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterfile</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />