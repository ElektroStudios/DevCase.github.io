# NativeMethods.MoveWindow Method (SafeHandle, Int32, Int32, Int32, Int32, Boolean)
 

Changes the position and dimensions of the specified window. 

 For a top-level window, the position and dimensions are relative to the upper-left corner of the screen. 

 For a child window, they are relative to the upper-left corner of the parent window's client area.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool MoveWindow(
	SafeHandle hWnd,
	int x,
	int y,
	int width,
	int height,
	bool repaint
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function MoveWindow ( 
	hWnd As SafeHandle,
	x As Integer,
	y As Integer,
	width As Integer,
	height As Integer,
	repaint As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim height As Integer
Dim repaint As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.MoveWindow(hWnd, 
	x, y, width, height, repaint)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool MoveWindow(
	SafeHandle^ hWnd, 
	int x, 
	int y, 
	int width, 
	int height, 
	bool repaint
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member MoveWindow : 
        hWnd : SafeHandle * 
        x : int * 
        y : int * 
        width : int * 
        height : int * 
        repaint : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window.</dd><dt>x</dt><dd>Type: System.Int32<br />The new position of the left side of the window.</dd><dt>y</dt><dd>Type: System.Int32<br />The new position of the top of the window.</dd><dt>width</dt><dd>Type: System.Int32<br />The new width of the window.</dd><dt>height</dt><dd>Type: System.Int32<br />The new height of the window.</dd><dt>repaint</dt><dd>Type: System.Boolean<br />Indicates whether the window is to be repainted. 

 If this parameter is `true` (`True` in Visual Basic), the window receives a message. If the parameter is `false` (`False` in Visual Basic), no repainting of any kind occurs. 

 This applies to the client area, the nonclient area (including the title bar and scroll bars), and any part of the parent window uncovered as a result of moving a child window.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633534%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633534%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MoveWindow">MoveWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />