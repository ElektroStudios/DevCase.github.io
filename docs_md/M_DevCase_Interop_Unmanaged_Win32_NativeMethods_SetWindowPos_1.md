# NativeMethods.SetWindowPos Method (SafeHandle, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)
 

Changes the size, position, and Z order of a child, pop-up, or top-level window. 

 These windows are ordered according to their appearance on the screen. 

 The topmost window receives the highest rank and is the first window in the Z order.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetWindowPos(
	SafeHandle hWnd,
	IntPtr hWndInsertAfter,
	int x,
	int y,
	int cx,
	int cy,
	SetWindowPosFlags uFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetWindowPos ( 
	hWnd As SafeHandle,
	hWndInsertAfter As IntPtr,
	x As Integer,
	y As Integer,
	cx As Integer,
	cy As Integer,
	uFlags As SetWindowPosFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hWndInsertAfter As IntPtr
Dim x As Integer
Dim y As Integer
Dim cx As Integer
Dim cy As Integer
Dim uFlags As SetWindowPosFlags
Dim returnValue As Boolean

returnValue = NativeMethods.SetWindowPos(hWnd, 
	hWndInsertAfter, x, y, cx, cy, uFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetWindowPos(
	SafeHandle^ hWnd, 
	IntPtr hWndInsertAfter, 
	int x, 
	int y, 
	int cx, 
	int cy, 
	SetWindowPosFlags uFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetWindowPos : 
        hWnd : SafeHandle * 
        hWndInsertAfter : IntPtr * 
        x : int * 
        y : int * 
        cx : int * 
        cy : int * 
        uFlags : SetWindowPosFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window.</dd><dt>hWndInsertAfter</dt><dd>Type: System.IntPtr<br />A handle to the window to precede the positioned window in the Z order.</dd><dt>x</dt><dd>Type: System.Int32<br />The new position of the left side of the window, in client coordinates.</dd><dt>y</dt><dd>Type: System.Int32<br />The new position of the top of the window, in client coordinates.</dd><dt>cx</dt><dd>Type: System.Int32<br />The new width of the window, in pixels.</dd><dt>cy</dt><dd>Type: System.Int32<br />The new height of the window, in pixels.</dd><dt>uFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SetWindowPosFlags">DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags</a><br />The window sizing and positioning flags.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633545(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633545(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPos">SetWindowPos Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />