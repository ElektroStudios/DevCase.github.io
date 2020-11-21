# NativeMethods.GetDlgItem Method (IntPtr, Int32)
 

Retrieves a handle to a control in the specified dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr GetDlgItem(
	IntPtr hWnd,
	int index
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetDlgItem ( 
	hWnd As IntPtr,
	index As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim index As Integer
Dim returnValue As IntPtr

returnValue = NativeMethods.GetDlgItem(hWnd, 
	index)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr GetDlgItem(
	IntPtr hWnd, 
	int index
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetDlgItem : 
        hWnd : IntPtr * 
        index : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the dialog box that contains the control .</dd><dt>index</dt><dd>Type: System.Int32<br />The index of the item to be retrieved.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the window handle of the specified control. 

 If the function fails, the return value is Zero, indicating an invalid dialog box handle or a nonexistent control.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645481%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645481%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDlgItem">GetDlgItem Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />