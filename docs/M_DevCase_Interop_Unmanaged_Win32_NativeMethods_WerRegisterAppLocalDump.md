# NativeMethods.WerRegisterAppLocalDump Method 
 

Registers a path relative to the local app store for the calling application where Windows Error Reporting (WER) should save a copy of the diagnostic memory dump that WER collects when one of the processes for the application stops responding.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerRegisterAppLocalDump(
	string localAppDataRelativePath
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerRegisterAppLocalDump ( 
	localAppDataRelativePath As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim localAppDataRelativePath As String
Dim returnValue As HResult

returnValue = NativeMethods.WerRegisterAppLocalDump(localAppDataRelativePath)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerRegisterAppLocalDump(
	String^ localAppDataRelativePath
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerRegisterAppLocalDump : 
        localAppDataRelativePath : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>localAppDataRelativePath</dt><dd>Type: System.String<br />The path relative to the local app store for the calling application where WER should save a copy of the diagnostic memory dump that WER collects when one of the processes for the application stops responding. 

 The maximum length for this relative path in characters is WER_MAX_LOCAL_DUMP_SUBPATH_LENGTH, which has a value of 64. This maximum length includes the null-termination character.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterapplocaldump" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisterapplocaldump</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />