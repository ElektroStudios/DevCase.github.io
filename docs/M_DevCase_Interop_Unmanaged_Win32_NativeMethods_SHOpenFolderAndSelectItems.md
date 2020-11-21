# NativeMethods.SHOpenFolderAndSelectItems Method 
 

Opens a Windows Explorer window with specified items in a particular folder selected.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static HResult SHOpenFolderAndSelectItems(
	PIDL pidlFolder,
	uint pidlCount,
	IntPtr[] pidlArray,
	OpenFolderFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHOpenFolderAndSelectItems ( 
	pidlFolder As PIDL,
	pidlCount As UInteger,
	pidlArray As IntPtr(),
	flags As OpenFolderFlags
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pidlFolder As PIDL
Dim pidlCount As UInteger
Dim pidlArray As IntPtr()
Dim flags As OpenFolderFlags
Dim returnValue As HResult

returnValue = NativeMethods.SHOpenFolderAndSelectItems(pidlFolder, 
	pidlCount, pidlArray, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static HResult SHOpenFolderAndSelectItems(
	PIDL^ pidlFolder, 
	unsigned int pidlCount, 
	[InAttribute] array<IntPtr>^ pidlArray, 
	OpenFolderFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHOpenFolderAndSelectItems : 
        pidlFolder : PIDL * 
        pidlCount : uint32 * 
        pidlArray : IntPtr[] * 
        flags : OpenFolderFlags -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pidlFolder</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to a fully qualified item ID list that specifies the folder.</dd><dt>pidlCount</dt><dd>Type: System.UInt32<br />A count of items in the *pidlArray* array. 

 If *pidlCount* is zero, then *pidlFolder* must point to a fully specified ITEMIDLIST describing a single item to select. 

 This function opens the parent folder and selects that item.</dd><dt>pidlArray</dt><dd>Type: System.IntPtr[]<br />A pointer to an array of PIDL structures, each of which is an item to select in the target folder referenced by *pidlFolder*.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_OpenFolderFlags">DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags</a><br />The optional flags.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.SHOpenFolderAndSelectItems(DevCase.Interop.Unmanaged.PIDL,System.UInt32,System.IntPtr[],DevCase.Interop.Unmanaged.Win32.Enums.OpenFolderFlags)"\]

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shopenfolderandselectitems" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shopenfolderandselectitems</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />