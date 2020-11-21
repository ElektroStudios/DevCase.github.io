# NativeMethods.ProgIDFromCLSID Method 
 

Retrieves the ProgID for a given CLSID.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)]
public static HResult ProgIDFromCLSID(
	in Guid refClsid,
	ref string refProgId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", CharSet := CharSet.Unicode, ExactSpelling := true>]
Public Shared Function ProgIDFromCLSID ( 
	ByRef refClsid As Guid,
	ByRef refProgId As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refClsid As Guid
Dim refProgId As String
Dim returnValue As HResult

returnValue = NativeMethods.ProgIDFromCLSID(refClsid, 
	refProgId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", CharSet = CharSet::Unicode, ExactSpelling = true)]
static HResult ProgIDFromCLSID(
	[InAttribute] Guid% refClsid, 
	String^% refProgId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", CharSet = CharSet.Unicode, ExactSpelling = true)>]
static member ProgIDFromCLSID : 
        refClsid : Guid byref * 
        refProgId : string byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refClsid</dt><dd>Type: System.Guid<br />The CLSID for which the ProgID is to be requested.</dd><dt>refProgId</dt><dd>Type: System.String<br />The address of a pointer variable that receives the ProgID string. 

 The string that represents clsid includes enclosing braces.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-progidfromclsid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-progidfromclsid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />