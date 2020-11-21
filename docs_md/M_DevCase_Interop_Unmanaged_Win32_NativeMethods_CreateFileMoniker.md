# NativeMethods.CreateFileMoniker Method 
 

Creates a file moniker based on the specified path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static HResult CreateFileMoniker(
	string pathName,
	out IMoniker refMoniker
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Function CreateFileMoniker ( 
	pathName As String,
	<OutAttribute> ByRef refMoniker As IMoniker
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pathName As String
Dim refMoniker As IMoniker
Dim returnValue As HResult

returnValue = NativeMethods.CreateFileMoniker(pathName, 
	refMoniker)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static HResult CreateFileMoniker(
	String^ pathName, 
	[OutAttribute] IMoniker^% refMoniker
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member CreateFileMoniker : 
        pathName : string * 
        refMoniker : IMoniker byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pathName</dt><dd>Type: System.String<br />The path on which this moniker is to be based. 

 This parameter can specify a relative path, a UNC path, or a drive-letter-based path. 

 If based on a relative path, the resulting moniker must be composed onto another file moniker before it can be bound.</dd><dt>refMoniker</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IMoniker<br />The address of an IMoniker* pointer variable that receives the interface pointer to the new file moniker. 

 When successful, the function has called AddRef on the file moniker and the caller is responsible for calling Release. 

 When an error occurs, the value of the interface pointer is NULL.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function can return the standard return values <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_UNEXPECTED</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">MK_E_SYNTAX</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/objbase/nf-objbase-createfilemoniker" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/objbase/nf-objbase-createfilemoniker</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />