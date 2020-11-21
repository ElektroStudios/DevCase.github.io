# NativeMethods.ILSaveToStream Method (IStream, IntPtr)
 

Saves an ITEMIDLIST structure to a stream.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult ILSaveToStream(
	IStream stream,
	IntPtr pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function ILSaveToStream ( 
	stream As IStream,
	pidl As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim stream As IStream
Dim pidl As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.ILSaveToStream(stream, 
	pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult ILSaveToStream(
	IStream^ stream, 
	IntPtr pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member ILSaveToStream : 
        stream : IStream * 
        pidl : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IStream<br />A pointer to the IStream interface where the ITEMIDLIST is saved.</dd><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to the ITEMIDLIST structure to be saved.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if successful, or a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error value otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilsavetostream" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilsavetostream</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ILSaveToStream">ILSaveToStream Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />