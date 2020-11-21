# NativeMethods.CLSIDFromProgID Method 
 

Looks up a CLSID in the registry, given a ProgID.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static HResult CLSIDFromProgID(
	string progId,
	out Guid refClsid
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Function CLSIDFromProgID ( 
	progId As String,
	<OutAttribute> ByRef refClsid As Guid
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim progId As String
Dim refClsid As Guid
Dim returnValue As HResult

returnValue = NativeMethods.CLSIDFromProgID(progId, 
	refClsid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static HResult CLSIDFromProgID(
	String^ progId, 
	[OutAttribute] Guid% refClsid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member CLSIDFromProgID : 
        progId : string * 
        refClsid : Guid byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>progId</dt><dd>Type: System.String<br />The ProgID whose CLSID is requested.</dd><dt>refClsid</dt><dd>Type: System.Guid<br />Receives the retrieved CLSID on return.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-clsidfromprogid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-clsidfromprogid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />