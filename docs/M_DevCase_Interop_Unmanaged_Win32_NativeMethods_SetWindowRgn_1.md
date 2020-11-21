# NativeMethods.SetWindowRgn Method (SafeHandle, SafeHandle, Boolean)
 

Sets the window region of a window. 

 The window region determines the area within the window where the system permits drawing. 

 The system does not display any portion of a window that lies outside of the window region

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetWindowRgn(
	SafeHandle hWnd,
	SafeHandle hRgn,
	bool redraw
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetWindowRgn ( 
	hWnd As SafeHandle,
	hRgn As SafeHandle,
	redraw As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hRgn As SafeHandle
Dim redraw As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SetWindowRgn(hWnd, 
	hRgn, redraw)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetWindowRgn(
	SafeHandle^ hWnd, 
	SafeHandle^ hRgn, 
	bool redraw
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetWindowRgn : 
        hWnd : SafeHandle * 
        hRgn : SafeHandle * 
        redraw : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose window region is to be set.</dd><dt>hRgn</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a region. The function sets the window region of the window to this region. 

 If *hRgn* is Zero, the function sets the window region to Zero.</dd><dt>redraw</dt><dd>Type: System.Boolean<br />Specifies whether the system redraws the window after setting the window region. If bRedraw is TRUE, the system does so; otherwise, it does not. 

 Typically, you set *redraw* to `true` (`True` in Visual Basic) if the window is visible.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setwindowrgn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setwindowrgn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowRgn">SetWindowRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />