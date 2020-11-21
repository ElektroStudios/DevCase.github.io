# NativeMethods.MapDialogRect Method (IntPtr, NativeRectangle)
 

Converts the specified dialog box units to screen units (pixels). 

 The function replaces the coordinates in the specified <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure with the converted coordinates, which allows the structure to be used to create a dialog box or position a control within a dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool MapDialogRect(
	IntPtr hDlg,
	ref NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function MapDialogRect ( 
	hDlg As IntPtr,
	ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDlg As IntPtr
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.MapDialogRect(hDlg, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool MapDialogRect(
	IntPtr hDlg, 
	NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member MapDialogRect : 
        hDlg : IntPtr * 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDlg</dt><dd>Type: System.IntPtr<br />A handle to a dialog box. 

 This function accepts only handles returned by one of the dialog box creation functions; handles for other windows are not valid.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the dialog box coordinates to be converted.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-mapdialogrect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-mapdialogrect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapDialogRect">MapDialogRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />