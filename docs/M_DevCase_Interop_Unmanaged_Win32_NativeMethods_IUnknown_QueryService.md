# NativeMethods.IUnknown_QueryService Method 
 

Retrieves an interface for a service from a specified object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult IUnknown_QueryService(
	IntPtr pUnk,
	ref Guid refGuidService,
	ref Guid refRiid,
	out IntPtr refPpvOut
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function IUnknown_QueryService ( 
	pUnk As IntPtr,
	ByRef refGuidService As Guid,
	ByRef refRiid As Guid,
	<OutAttribute> ByRef refPpvOut As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pUnk As IntPtr
Dim refGuidService As Guid
Dim refRiid As Guid
Dim refPpvOut As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.IUnknown_QueryService(pUnk, 
	refGuidService, refRiid, refPpvOut)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult IUnknown_QueryService(
	IntPtr pUnk, 
	Guid% refGuidService, 
	Guid% refRiid, 
	[OutAttribute] IntPtr% refPpvOut
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member IUnknown_QueryService : 
        pUnk : IntPtr * 
        refGuidService : Guid byref * 
        refRiid : Guid byref * 
        refPpvOut : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pUnk</dt><dd>Type: System.IntPtr<br />A pointer to the IUnknown instance of the COM object that supports the service..</dd><dt>refGuidService</dt><dd>Type: System.Guid<br />The service's unique identifier (SID).</dd><dt>refRiid</dt><dd>Type: System.Guid<br />The IID of the desired service interface.</dd><dt>refPpvOut</dt><dd>Type: System.IntPtr<br />When this method returns, contains the interface pointer requested *refRiid*. 

 If successful, the calling application is responsible for calling `IUnknown.Release()` method using this value when the service is no longer needed. 

 In the case of failure, this value is NULL</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if successful. 

 Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_FAIL</a> if the object does not support IServiceProvider. Otherwise, the function returns the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value returned by the object's `QueryService` method.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb759858(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb759858(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />