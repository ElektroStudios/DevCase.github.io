# NativeMethods.CLSIDFromProgIDEx Method 
 

Looks up a CLSID in the registry, given a ProgID, and triggers automatic installation if the COMClassStore policy is enabled. 

 This is analogous to the behavior of CoCreateInstance when neither CLSCTX_ENABLE_CODE_DOWNLOAD nor CLSCTX_NO_CODE_DOWNLOAD are specified.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static HResult CLSIDFromProgIDEx(
	string progId,
	out Guid refClsid
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Function CLSIDFromProgIDEx ( 
	progId As String,
	<OutAttribute> ByRef refClsid As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim progId As String
Dim refClsid As Guid
Dim returnValue As HResult

returnValue = NativeMethods.CLSIDFromProgIDEx(progId, 
	refClsid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static HResult CLSIDFromProgIDEx(
	String^ progId, 
	[OutAttribute] Guid% refClsid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member CLSIDFromProgIDEx : 
        progId : string * 
        refClsid : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>progId</dt><dd>Type: System.String<br />A pointer to the ProgID whose CLSID is requested.</dd><dt>refClsid</dt><dd>Type: System.Guid<br />Receives a pointer to the retrieved CLSID on return.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-clsidfromprogidex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-clsidfromprogidex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />