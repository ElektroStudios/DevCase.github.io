# NativeMethods.SHCreateItemFromParsingName Method (String, IntPtr, Guid, IShellItem)
 

Creates and initializes a Shell item object from a parsing name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static HResult SHCreateItemFromParsingName(
	string path,
	IntPtr pbc,
	ref Guid refIID,
	ref IShellItem refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SHCreateItemFromParsingName ( 
	path As String,
	pbc As IntPtr,
	ByRef refIID As Guid,
	ByRef refShellItem As IShellItem
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim pbc As IntPtr
Dim refIID As Guid
Dim refShellItem As IShellItem
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateItemFromParsingName(path, 
	pbc, refIID, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static HResult SHCreateItemFromParsingName(
	String^ path, 
	IntPtr pbc, 
	Guid% refIID, 
	IShellItem^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHCreateItemFromParsingName : 
        path : string * 
        pbc : IntPtr * 
        refIID : Guid byref * 
        refShellItem : IShellItem byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A display name.</dd><dt>pbc</dt><dd>Type: System.IntPtr<br />Optional. A pointer to a bind context used to pass parameters as inputs and outputs to the parsing function. 

 These passed parameters are often specific to the data source and are documented by the data source owners. 

 For example, the file system data source accepts the name being parsed (as a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW</a> structure), using the STR_FILE_SYS_BIND_DATA bind context parameter.</dd><dt>refIID</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve through ppv, typically IID_IShellItem or IID_IShellItem2.</dd><dt>refShellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />When this method returns successfully, contains the interface pointer requested in *refIID*. This is typically <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> or IShellItem2.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromparsingname" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromparsingname</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemFromParsingName">SHCreateItemFromParsingName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />