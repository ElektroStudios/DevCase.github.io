# NativeMethods.PickIconDlg Method (IntPtr, String, Int32, Int32)
 

Displays a dialog box that allows the user to choose an icon from the selection available embedded in a resource such as an executable or DLL file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PickIconDlg(
	IntPtr hWnd,
	string iconPath,
	int iconPathSize,
	ref int refIconIndex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PickIconDlg ( 
	hWnd As IntPtr,
	iconPath As String,
	iconPathSize As Integer,
	ByRef refIconIndex As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim iconPath As String
Dim iconPathSize As Integer
Dim refIconIndex As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.PickIconDlg(hWnd, 
	iconPath, iconPathSize, refIconIndex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PickIconDlg(
	IntPtr hWnd, 
	String^ iconPath, 
	int iconPathSize, 
	int% refIconIndex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PickIconDlg : 
        hWnd : IntPtr * 
        iconPath : string * 
        iconPathSize : int * 
        refIconIndex : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The handle of the parent window. This value can be Zero.</dd><dt>iconPath</dt><dd>Type: System.String<br />A pointer to a string that contains the null-terminated, fully qualified path of the default resource that contains the icons. 

 If the user chooses a different resource in the dialog, this buffer contains the path of that file when the function returns. 

 This buffer should be at least MAX_PATH characters in length, or the returned path may be truncated. 

 You should verify that the path is valid before using it.</dd><dt>iconPathSize</dt><dd>Type: System.Int32<br />The number of characters in *iconPath*, including the terminating NULL character.</dd><dt>refIconIndex</dt><dd>Type: System.Int32<br />A pointer to an integer that on entry specifies the index of the initial selection and, when this function returns successfully, receives the index of the icon that was selected.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pickicondlg" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pickicondlg</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_PickIconDlg">PickIconDlg Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />