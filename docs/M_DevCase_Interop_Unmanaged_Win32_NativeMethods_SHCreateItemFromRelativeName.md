# NativeMethods.SHCreateItemFromRelativeName Method (IShellItem, String, IBindCtx, Guid, IShellItem)
 

Creates and initializes a Shell item object from a relative parsing name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[SecurityCriticalAttribute]
public static HResult SHCreateItemFromRelativeName(
	IShellItem parent,
	string name,
	IBindCtx bindContext,
	ref Guid refIid,
	out IShellItem refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
<SecurityCriticalAttribute>
Public Shared Function SHCreateItemFromRelativeName ( 
	parent As IShellItem,
	name As String,
	bindContext As IBindCtx,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refShellItem As IShellItem
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim parent As IShellItem
Dim name As String
Dim bindContext As IBindCtx
Dim refIid As Guid
Dim refShellItem As IShellItem
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateItemFromRelativeName(parent, 
	name, bindContext, refIid, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[SecurityCriticalAttribute]
static HResult SHCreateItemFromRelativeName(
	[InAttribute] IShellItem^ parent, 
	[InAttribute] String^ name, 
	[InAttribute] IBindCtx^ bindContext, 
	Guid% refIid, 
	[OutAttribute] IShellItem^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
[<SecurityCriticalAttribute>]
static member SHCreateItemFromRelativeName : 
        parent : IShellItem * 
        name : string * 
        bindContext : IBindCtx * 
        refIid : Guid byref * 
        refShellItem : IShellItem byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>parent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />A pointer to the parent Shell item.</dd><dt>name</dt><dd>Type: System.String<br />A pointer to a null-terminated, Unicode string that specifies a display name that is relative to the *parent*.</dd><dt>bindContext</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />A pointer to a bind context that controls the parsing operation. This parameter can be NULL.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to an interface ID, typically IID_IShellItem or IID_IShellItem2.</dd><dt>refShellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />When this function returns, contains the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> interface pointer requested in *refIid*.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromrelativename" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromrelativename</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemFromRelativeName">SHCreateItemFromRelativeName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />