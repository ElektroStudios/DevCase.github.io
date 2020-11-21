# NativeMethods.WerUnregisterCustomMetadata Method 
 

Removes an item of app-specific metadata being collected during error reporting for the application.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerUnregisterCustomMetadata(
	string key
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerUnregisterCustomMetadata ( 
	key As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim key As String
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterCustomMetadata(key)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerUnregisterCustomMetadata(
	String^ key
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerUnregisterCustomMetadata : 
        key : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.String<br />The "key" string for the metadata element being removed. 

 It must have been previously registered with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterCustomMetadata">WerRegisterCustomMetadata(String, String)</a> function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregistercustommetadata" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregistercustommetadata</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />