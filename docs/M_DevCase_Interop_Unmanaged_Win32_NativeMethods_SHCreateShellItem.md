# NativeMethods.SHCreateShellItem Method 
 

Creates an IShellItem object. 

 Note: It is recommended that you use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemWithParent">SHCreateItemWithParent(PIDL, IShellFolder, PIDL, Guid, IShellItem)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHCreateItemFromIDList">SHCreateItemFromIDList(PIDL, Guid, IShellItem)</a> instead of this function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static HResult SHCreateShellItem(
	PIDL pidlParent,
	IShellFolder folderParent,
	PIDL pidl,
	out IShellItem refShellItem
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Function SHCreateShellItem ( 
	pidlParent As PIDL,
	folderParent As IShellFolder,
	pidl As PIDL,
	<OutAttribute> ByRef refShellItem As IShellItem
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pidlParent As PIDL
Dim folderParent As IShellFolder
Dim pidl As PIDL
Dim refShellItem As IShellItem
Dim returnValue As HResult

returnValue = NativeMethods.SHCreateShellItem(pidlParent, 
	folderParent, pidl, refShellItem)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static HResult SHCreateShellItem(
	PIDL^ pidlParent, 
	IShellFolder^ folderParent, 
	PIDL^ pidl, 
	[OutAttribute] IShellItem^% refShellItem
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member SHCreateShellItem : 
        pidlParent : PIDL * 
        folderParent : IShellFolder * 
        pidl : PIDL * 
        refShellItem : IShellItem byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pidlParent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A PIDL to the parent. This value can be NULL.</dd><dt>folderParent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellFolder</a><br />A pointer to the parent <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a>. This value can be NULL.</dd><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A PIDL to the requested item. 

 If parent information is not included in *pidlParent* or *folderParent*, this must be an absolute PIDL.</dd><dt>refShellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />When this method returns, contains the interface pointer to the new <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shcreateshellitem" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shcreateshellitem</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />