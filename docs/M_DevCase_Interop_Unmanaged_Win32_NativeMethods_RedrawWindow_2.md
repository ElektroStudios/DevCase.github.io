# NativeMethods.RedrawWindow Method (IntPtr, IntPtr, IntPtr, RedrawWindowFlags)
 

Updates the specified rectangle or region in a window's client area.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool RedrawWindow(
	IntPtr hWnd,
	IntPtr lprcUpdate,
	IntPtr hrgnUpdate,
	RedrawWindowFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function RedrawWindow ( 
	hWnd As IntPtr,
	lprcUpdate As IntPtr,
	hrgnUpdate As IntPtr,
	flags As RedrawWindowFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim lprcUpdate As IntPtr
Dim hrgnUpdate As IntPtr
Dim flags As RedrawWindowFlags
Dim returnValue As Boolean

returnValue = NativeMethods.RedrawWindow(hWnd, 
	lprcUpdate, hrgnUpdate, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool RedrawWindow(
	IntPtr hWnd, 
	IntPtr lprcUpdate, 
	IntPtr hrgnUpdate, 
	RedrawWindowFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member RedrawWindow : 
        hWnd : IntPtr * 
        lprcUpdate : IntPtr * 
        hrgnUpdate : IntPtr * 
        flags : RedrawWindowFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be redrawn. 

 If this parameter is Zero, the desktop window is updated.</dd><dt>lprcUpdate</dt><dd>Type: System.IntPtr<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure containing the coordinates, in device units, of the update rectangle. 

 This parameter is ignored if the *hrgnUpdate* parameter identifies a region.</dd><dt>hrgnUpdate</dt><dd>Type: System.IntPtr<br />A handle to the update region. 

 If both the *hrgnUpdate* and *lprcUpdate* parameters are Zero, the entire client area is added to the update region.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RedrawWindowFlags">DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags</a><br />One or more redraw flags. 

 This parameter can be used to invalidate or validate a window, control repainting, and control which windows are affected by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow(IntPtr, NativeRectangle, IntPtr, RedrawWindowFlags)</a></dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />