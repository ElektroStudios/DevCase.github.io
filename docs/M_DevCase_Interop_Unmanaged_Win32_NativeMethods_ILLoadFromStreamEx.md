# NativeMethods.ILLoadFromStreamEx Method (IStream, PIDL)
 

Loads an absolute ITEMIDLIST from an IStream.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult ILLoadFromStreamEx(
	IStream stream,
	out PIDL refPidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function ILLoadFromStreamEx ( 
	stream As IStream,
	<OutAttribute> ByRef refPidl As PIDL
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim stream As IStream
Dim refPidl As PIDL
Dim returnValue As HResult

returnValue = NativeMethods.ILLoadFromStreamEx(stream, 
	refPidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult ILLoadFromStreamEx(
	IStream^ stream, 
	[OutAttribute] PIDL^% refPidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member ILLoadFromStreamEx : 
        stream : IStream * 
        refPidl : PIDL byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IStream<br />A pointer to the IStream interface from which the absolute ITEMIDLIST loads.</dd><dt>refPidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />When this method returns and succeeds, contains the resulting absolute ITEMIDLIST. 

 If it fails, contains Zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if successful, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error value otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-illoadfromstreamex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-illoadfromstreamex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ILLoadFromStreamEx">ILLoadFromStreamEx Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />