# NativeMethods.ILFindChild Method (PIDL, PIDL)
 

Determines whether a specified ITEMIDLIST structure is the child of another ITEMIDLIST structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static PIDL ILFindChild(
	PIDL pidlParent,
	PIDL pidlChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Function ILFindChild ( 
	pidlParent As PIDL,
	pidlChild As PIDL
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim pidlParent As PIDL
Dim pidlChild As PIDL
Dim returnValue As PIDL

returnValue = NativeMethods.ILFindChild(pidlParent, 
	pidlChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static PIDL^ ILFindChild(
	PIDL^ pidlParent, 
	PIDL^ pidlChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member ILFindChild : 
        pidlParent : PIDL * 
        pidlChild : PIDL -> PIDL 

```


#### Parameters
&nbsp;<dl><dt>pidlParent</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to the parent ITEMIDLIST structure.</dd><dt>pidlChild</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to the child ITEMIDLIST structure.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />Returns a pointer to the child's simple ITEMIDLIST structure if *pidlChild* is a child of *pidlParent*. 

 The returned structure consists of *pidlChild*, minus the SHITEMID structures that make up *pidlParent*. 

 Returns Zero if *pidlChild* is not a child of *pidlParent*. 

 Note: The returned pointer is a pointer into the existing parent structure. It is an alias for *pidlChild*. No new memory is allocated in association with the returned pointer. It is not the caller's responsibility to free the returned value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfindchild" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-ilfindchild</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ILFindChild">ILFindChild Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />