# NativeMethods.SHFindFiles Method 
 

Displays the Search window UI.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static bool SHFindFiles(
	IntPtr pidlFolder,
	[OptionalAttribute] IntPtr reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHFindFiles ( 
	pidlFolder As IntPtr,
	<OptionalAttribute> reserved As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidlFolder As IntPtr
Dim reserved As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SHFindFiles(pidlFolder, 
	reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static bool SHFindFiles(
	IntPtr pidlFolder, 
	[OptionalAttribute] IntPtr reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHFindFiles : 
        pidlFolder : IntPtr * 
        [<OptionalAttribute>] reserved : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidlFolder</dt><dd>Type: System.IntPtr<br />The folder from which to start the search. 

 This folder appears in the Look in: box in the Search window. 

 This folder and all of its subfolders are searched unless users choose other options in the Search window's More Advanced Options. 

 This value can be Zero.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />This parameter is not used and must be set to Zero.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful in displaying the Search window; otherwise `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shfindfiles" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shfindfiles</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />