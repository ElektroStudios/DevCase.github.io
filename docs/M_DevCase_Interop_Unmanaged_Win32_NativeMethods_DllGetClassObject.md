# NativeMethods.DllGetClassObject Method 
 

Retrieves the class object from a DLL object handler or object application. 

 OLE does not provide this function. DLLs that support the OLE Component Object Model (COM) must implement DllGetClassObject in OLE object handlers or DLL applications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static HResult DllGetClassObject(
	ref Guid refClsid,
	ref Guid refIid,
	out Object refPv
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Function DllGetClassObject ( 
	ByRef refClsid As Guid,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refPv As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim refClsid As Guid
Dim refIid As Guid
Dim refPv As Object
Dim returnValue As HResult

returnValue = NativeMethods.DllGetClassObject(refClsid, 
	refIid, refPv)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static HResult DllGetClassObject(
	Guid% refClsid, 
	Guid% refIid, 
	[OutAttribute] Object^% refPv
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member DllGetClassObject : 
        refClsid : Guid byref * 
        refIid : Guid byref * 
        refPv : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refClsid</dt><dd>Type: System.Guid<br />The CLSID that will associate the correct data and code.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the identifier of the interface that the caller is to use to communicate with the class object. 

 Usually, this is IID_IClassFactory (defined in the OLE headers as the interface identifier for IClassFactory).</dd><dt>refPv</dt><dd>Type: System.Object<br />The address of a pointer variable that receives the interface pointer requested in *refIid*. 

 Upon successful return, *refPv* contains the requested interface pointer. 

 If an error occurs, the interface pointer is NULL.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-dllgetclassobject" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/combaseapi/nf-combaseapi-dllgetclassobject</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />