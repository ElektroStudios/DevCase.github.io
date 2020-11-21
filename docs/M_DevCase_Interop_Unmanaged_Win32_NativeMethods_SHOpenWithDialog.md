# NativeMethods.SHOpenWithDialog Method 
 

Displays the Open With dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static HResult SHOpenWithDialog(
	IntPtr hWndParent,
	ref OpenAsInfo refOpenAsInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Function SHOpenWithDialog ( 
	hWndParent As IntPtr,
	ByRef refOpenAsInfo As OpenAsInfo
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As IntPtr
Dim refOpenAsInfo As OpenAsInfo
Dim returnValue As HResult

returnValue = NativeMethods.SHOpenWithDialog(hWndParent, 
	refOpenAsInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static HResult SHOpenWithDialog(
	IntPtr hWndParent, 
	OpenAsInfo% refOpenAsInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member SHOpenWithDialog : 
        hWndParent : IntPtr * 
        refOpenAsInfo : OpenAsInfo byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.IntPtr<br />The handle of the parent window. This value can be NULL.</dd><dt>refOpenAsInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OpenAsInfo">DevCase.Interop.Unmanaged.Win32.Structures.OpenAsInfo</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_OpenAsInfo">OpenAsInfo</a> structure, which specifies the contents of the resulting dialog.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shopenwithdialog" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shopenwithdialog</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />