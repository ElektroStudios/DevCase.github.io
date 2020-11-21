# NativeMethods.SHCreateItemFromParsingName Method (String, IBindCtx, Guid, Object)
 

Creates and initializes a Shell item object from a parsing name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult SHCreateItemFromParsingName(
	string path,
	[OptionalAttribute] IBindCtx bindContext,
	ref Guid refIid,
	out Object refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function SHCreateItemFromParsingName ( 
	path As String,
	<OptionalAttribute> bindContext As IBindCtx,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refShellItem As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim bindContext As IBindCtx
Dim refIid As Guid
Dim refShellItem As Object
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateItemFromParsingName(path, 
	bindContext, refIid, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult SHCreateItemFromParsingName(
	[InAttribute] String^ path, 
	[OptionalAttribute] [InAttribute] IBindCtx^ bindContext, 
	Guid% refIid, 
	[OutAttribute] Object^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member SHCreateItemFromParsingName : 
        path : string * 
        [<OptionalAttribute>] bindContext : IBindCtx * 
        refIid : Guid byref * 
        refShellItem : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a display name.</dd><dt>bindContext (Optional)</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />Optional. A pointer to a bind context used to pass parameters as inputs and outputs to the parsing function. 

 These passed parameters are often specific to the data source and are documented by the data source owners. 

 For example, the file system data source accepts the name being parsed (as a WIN32_FIND_DATA structure), using the STR_FILE_SYS_BIND_DATA bind context parameter.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve through *refShellItem*, typically IID_IShellItem or IID_IShellItem2.</dd><dt>refShellItem</dt><dd>Type: System.Object<br />When this function returns, contains the interface pointer requested in *refIid*. This will usually be <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> or IShellItem2.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromparsingname" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromparsingname</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemFromParsingName">SHCreateItemFromParsingName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />