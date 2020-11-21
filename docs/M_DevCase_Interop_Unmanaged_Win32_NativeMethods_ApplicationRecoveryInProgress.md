# NativeMethods.ApplicationRecoveryInProgress Method 
 

Indicates that the calling application is continuing to recover data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult ApplicationRecoveryInProgress(
	out bool refCanceled
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function ApplicationRecoveryInProgress ( 
	<OutAttribute> ByRef refCanceled As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refCanceled As Boolean
Dim returnValue As HResult

returnValue = NativeMethods.ApplicationRecoveryInProgress(refCanceled)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult ApplicationRecoveryInProgress(
	[OutAttribute] bool% refCanceled
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member ApplicationRecoveryInProgress : 
        refCanceled : bool byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refCanceled</dt><dd>Type: System.Boolean<br />Indicates whether the user has canceled the recovery process. Set by Windows Error Reporting (WER) if the user clicks the Cancel button.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on fail.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-applicationrecoveryinprogress" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-applicationrecoveryinprogress</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />