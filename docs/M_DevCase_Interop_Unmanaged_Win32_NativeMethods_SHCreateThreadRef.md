# NativeMethods.SHCreateThreadRef Method 
 

Creates a per-thread reference to a Component Object Model (COM) object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", ExactSpelling = true)]
public static HResult SHCreateThreadRef(
	ref int refRef,
	out Object refPunk
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", ExactSpelling := true>]
Public Shared Function SHCreateThreadRef ( 
	ByRef refRef As Integer,
	<OutAttribute> ByRef refPunk As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refRef As Integer
Dim refPunk As Object
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateThreadRef(refRef, 
	refPunk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", ExactSpelling = true)]
static HResult SHCreateThreadRef(
	int% refRef, 
	[OutAttribute] Object^% refPunk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", ExactSpelling = true)>]
static member SHCreateThreadRef : 
        refRef : int byref * 
        refPunk : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refRef</dt><dd>Type: System.Int32<br />A pointer to a value, usually a local variable in the thread's ThreadProc, that is used by the interface in *refPunk* as a reference counter.</dd><dt>refPunk</dt><dd>Type: System.Object<br />The address of a pointer to an IUnknown interface. 

 If successful, this parameter holds the thread's IUnknown pointer on return. 

 Your application is responsible for freeing the pointer when it is finished.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shcreatethreadref" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shcreatethreadref</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />