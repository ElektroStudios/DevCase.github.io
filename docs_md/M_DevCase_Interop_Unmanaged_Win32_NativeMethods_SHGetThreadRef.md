# NativeMethods.SHGetThreadRef Method 
 

Retrieves the per-thread object reference set by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHSetThreadRef">SHSetThreadRef(Object)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true)]
public static HResult SHGetThreadRef(
	out Object refPunk
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true>]
Public Shared Function SHGetThreadRef ( 
	<OutAttribute> ByRef refPunk As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refPunk As Object
Dim returnValue As HResult

returnValue = NativeMethods.SHGetThreadRef(refPunk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true)]
static HResult SHGetThreadRef(
	[OutAttribute] Object^% refPunk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true)>]
static member SHGetThreadRef : 
        refPunk : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refPunk</dt><dd>Type: System.Object<br />The address of a pointer that, when this function returns successfully, points to the object whose reference is stored. 

 Your application is responsible for freeing this resource when it is no longer needed..</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the object reference exists, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_NOINTERFACE</a> otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shgetthreadref" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shgetthreadref</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />