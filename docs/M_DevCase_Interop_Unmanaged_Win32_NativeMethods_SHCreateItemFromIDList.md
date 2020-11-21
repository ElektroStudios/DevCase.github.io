# NativeMethods.SHCreateItemFromIDList Method (PIDL, Guid, IShellItem)
 

Creates and initializes a Shell item object from a pointer to an item identifier list (PIDL). 

 The resulting shell item object supports the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> interface.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static HResult SHCreateItemFromIDList(
	PIDL pidl,
	ref Guid refIid,
	out IShellItem refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Function SHCreateItemFromIDList ( 
	pidl As PIDL,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refShellItem As IShellItem
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pidl As PIDL
Dim refIid As Guid
Dim refShellItem As IShellItem
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateItemFromIDList(pidl, 
	refIid, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static HResult SHCreateItemFromIDList(
	PIDL^ pidl, 
	Guid% refIid, 
	[OutAttribute] IShellItem^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member SHCreateItemFromIDList : 
        pidl : PIDL * 
        refIid : Guid byref * 
        refShellItem : IShellItem byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The source PIDL.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve through *refShellItem*, typically IID_IShellItem or IID_IShellItem2.</dd><dt>refShellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />When this function returns, contains the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> interface pointer requested in *refIid*.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromidlist" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemfromidlist</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemFromIDList">SHCreateItemFromIDList Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />