# NativeMethods.SHAutoComplete Method 
 

Instructs system edit controls to use AutoComplete to help complete URLs or file system paths.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll")]
public static HResult SHAutoComplete(
	IntPtr hWndEdit,
	AutoCompleteFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll">]
Public Shared Function SHAutoComplete ( 
	hWndEdit As IntPtr,
	flags As AutoCompleteFlags
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWndEdit As IntPtr
Dim flags As AutoCompleteFlags
Dim returnValue As HResult

returnValue = NativeMethods.SHAutoComplete(hWndEdit, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll")]
static HResult SHAutoComplete(
	IntPtr hWndEdit, 
	AutoCompleteFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll")>]
static member SHAutoComplete : 
        hWndEdit : IntPtr * 
        flags : AutoCompleteFlags -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWndEdit</dt><dd>Type: System.IntPtr<br />The window handle of a system edit control. Typically, this parameter is the handle of an edit control or the edit control embedded in a ComboBoxEx control.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AutoCompleteFlags">DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags</a><br />Flags that control the AutoComplete operation.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shautocomplete" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-shautocomplete</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />