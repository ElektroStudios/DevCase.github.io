# NativeMethods.ListBoxItemFromPoint Method (IntPtr, NativePoint, Boolean)
 

Retrieves the index of the item at the specified point in a list box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", EntryPoint = "LBItemFromPt", SetLastError = true)]
public static int ListBoxItemFromPoint(
	IntPtr hWnd,
	NativePoint pt,
	bool autoScroll
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", EntryPoint := "LBItemFromPt", SetLastError := true>]
Public Shared Function ListBoxItemFromPoint ( 
	hWnd As IntPtr,
	pt As NativePoint,
	autoScroll As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim pt As NativePoint
Dim autoScroll As Boolean
Dim returnValue As Integer

returnValue = NativeMethods.ListBoxItemFromPoint(hWnd, 
	pt, autoScroll)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", EntryPoint = L"LBItemFromPt", SetLastError = true)]
static int ListBoxItemFromPoint(
	IntPtr hWnd, 
	NativePoint pt, 
	bool autoScroll
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", EntryPoint = "LBItemFromPt", SetLastError = true)>]
static member ListBoxItemFromPoint : 
        hWnd : IntPtr * 
        pt : NativePoint * 
        autoScroll : bool -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the list box to check.</dd><dt>pt</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that contains the screen coordinates to check.</dd><dt>autoScroll</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic) and the point is directly above or below the list box, the function scrolls the list box by one line and returns -1. Otherwise, the function does not scroll the list box.</dd></dl>

#### Return Value
Type: Int32<br />Returns the item identifier if the point is over a list item, or -1 otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-lbitemfrompt" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-lbitemfrompt</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ListBoxItemFromPoint">ListBoxItemFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />