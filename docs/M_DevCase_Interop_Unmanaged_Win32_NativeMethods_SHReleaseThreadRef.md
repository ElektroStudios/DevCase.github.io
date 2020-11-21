# NativeMethods.SHReleaseThreadRef Method 
 

Releases a thread reference before the thread procedure returns.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true)]
public static HResult SHReleaseThreadRef()
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true>]
Public Shared Function SHReleaseThreadRef As HResult
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As HResult

returnValue = NativeMethods.SHReleaseThreadRef()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true)]
static HResult SHReleaseThreadRef()
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true)>]
static member SHReleaseThreadRef : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shreleasethreadref" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shreleasethreadref</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />