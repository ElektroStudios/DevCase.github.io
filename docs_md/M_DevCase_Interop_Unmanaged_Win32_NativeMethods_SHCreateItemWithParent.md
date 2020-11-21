# NativeMethods.SHCreateItemWithParent Method (PIDL, IShellFolder, PIDL, Guid, IShellItem)
 

Create a Shell item, given a parent folder and a child item ID.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[SecurityCriticalAttribute]
public static HResult SHCreateItemWithParent(
	PIDL pidlParent,
	IShellFolder folderParent,
	PIDL pidl,
	ref Guid refIid,
	out IShellItem refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
<SecurityCriticalAttribute>
Public Shared Function SHCreateItemWithParent ( 
	pidlParent As PIDL,
	folderParent As IShellFolder,
	pidl As PIDL,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refShellItem As IShellItem
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pidlParent As PIDL
Dim folderParent As IShellFolder
Dim pidl As PIDL
Dim refIid As Guid
Dim refShellItem As IShellItem
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateItemWithParent(pidlParent, 
	folderParent, pidl, refIid, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
[SecurityCriticalAttribute]
static HResult SHCreateItemWithParent(
	[InAttribute] PIDL^ pidlParent, 
	[InAttribute] IShellFolder^ folderParent, 
	[InAttribute] PIDL^ pidl, 
	Guid% refIid, 
	[OutAttribute] IShellItem^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
[<SecurityCriticalAttribute>]
static member SHCreateItemWithParent : 
        pidlParent : PIDL * 
        folderParent : IShellFolder * 
        pidl : PIDL * 
        refIid : Guid byref * 
        refShellItem : IShellItem byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pidlParent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The IDList of the parent folder of the item being created; the IDList of *folderParent*. 

 This parameter can be NULL, if psfParent is specified.</dd><dt>folderParent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellFolder</a><br />A pointer to <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a> interface that specifies the shell data source of the child item specified by the *pidl*. 

 This parameter can be NULL, if *pidlParent* is specified.</dd><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A child item ID relative to its parent folder specified by *pidlParent* or *folderParent*.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve through *refShellItem*, typically IID_IShellItem or IID_IShellItem2.</dd><dt>refShellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />When this function returns, contains the interface pointer requested in *refIid*. This will typically be <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> or IShellItem2.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemwithparent" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shcreateitemwithparent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemWithParent">SHCreateItemWithParent Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />