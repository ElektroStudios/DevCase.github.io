# NativeMethods.RedrawWindow Method (SafeHandle, Rectangle, IntPtr, RedrawWindowFlags)
 

Updates the specified rectangle or region in a window's client area.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool RedrawWindow(
	SafeHandle hWnd,
	in Rectangle refRectUpdate,
	IntPtr refRegionUpdate,
	RedrawWindowFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function RedrawWindow ( 
	hWnd As SafeHandle,
	ByRef refRectUpdate As Rectangle,
	refRegionUpdate As IntPtr,
	flags As RedrawWindowFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refRectUpdate As Rectangle
Dim refRegionUpdate As IntPtr
Dim flags As RedrawWindowFlags
Dim returnValue As Boolean

returnValue = NativeMethods.RedrawWindow(hWnd, 
	refRectUpdate, refRegionUpdate, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool RedrawWindow(
	SafeHandle^ hWnd, 
	[InAttribute] Rectangle% refRectUpdate, 
	IntPtr refRegionUpdate, 
	RedrawWindowFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member RedrawWindow : 
        hWnd : SafeHandle * 
        refRectUpdate : Rectangle byref * 
        refRegionUpdate : IntPtr * 
        flags : RedrawWindowFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to be redrawn. 

 If this parameter is Zero, the desktop window is updated.</dd><dt>refRectUpdate</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to a Rectangle structure containing the coordinates, in device units, of the update rectangle. 

 This parameter is ignored if the *refRegionUpdate* parameter identifies a region.</dd><dt>refRegionUpdate</dt><dd>Type: System.IntPtr<br />A handle to the update region. 

 If both the *refRegionUpdate* and *refRectUpdate* parameters are Zero, the entire client area is added to the update region.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RedrawWindowFlags">DevCase.Interop.Unmanaged.Win32.Enums.RedrawWindowFlags</a><br />One or more redraw flags. 

 This parameter can be used to invalidate or validate a window, control repainting, and control which windows are affected by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow(IntPtr, NativeRectangle, IntPtr, RedrawWindowFlags)</a></dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162911%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_RedrawWindow">RedrawWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />