# NativeMethods.WerRegisterCustomMetadata Method 
 

Registers app-specific metadata to be collected (in the form of key/value strings) when WER creates an error report.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerRegisterCustomMetadata(
	string key,
	string value
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerRegisterCustomMetadata ( 
	key As String,
	value As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim key As String
Dim value As String
Dim returnValue As HResult

returnValue = NativeMethods.WerRegisterCustomMetadata(key, 
	value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerRegisterCustomMetadata(
	String^ key, 
	String^ value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerRegisterCustomMetadata : 
        key : string * 
        value : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.String<br />The "key" string for the metadata element being registered.</dd><dt>value</dt><dd>Type: System.String<br />The value string for the metadata element being registered.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregistercustommetadata" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregistercustommetadata</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />