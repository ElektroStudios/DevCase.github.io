# NativeMethods.SHSetThreadRef Method 
 

Stores a per-thread reference to a Component Object Model (COM) object. 

 This allows the caller to control the thread's lifetime so that it can ensure that Windows won't shut down the thread before the caller is ready.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true)]
public static HResult SHSetThreadRef(
	Object punk
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true>]
Public Shared Function SHSetThreadRef ( 
	punk As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim punk As Object
Dim returnValue As HResult

returnValue = NativeMethods.SHSetThreadRef(punk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true)]
static HResult SHSetThreadRef(
	Object^ punk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true)>]
static member SHSetThreadRef : 
        punk : Object -> HResult 

```


#### Parameters
&nbsp;<dl><dt>punk</dt><dd>Type: System.Object<br />A pointer to the IUnknown of the object for which you want to store a reference. This value can be NULL.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shsetthreadref" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shsetthreadref</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />