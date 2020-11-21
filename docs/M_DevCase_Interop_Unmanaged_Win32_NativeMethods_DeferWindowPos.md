# NativeMethods.DeferWindowPos Method 
 

Updates the specified multiple-window – position structure for the specified window. 

 The function then returns a handle to the updated structure. 

 The DeferWindowPos(IntPtr, IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags) function uses the information in this structure to change the position and size of a number of windows simultaneously. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginDeferWindowPos">BeginDeferWindowPos(Int32)</a> function creates the structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr DeferWindowPos(
	IntPtr hWinPosInfo,
	IntPtr hWnd,
	IntPtr hWndInsertAfter,
	int x,
	int y,
	int width,
	int heigth,
	SetWindowPosFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function DeferWindowPos ( 
	hWinPosInfo As IntPtr,
	hWnd As IntPtr,
	hWndInsertAfter As IntPtr,
	x As Integer,
	y As Integer,
	width As Integer,
	heigth As Integer,
	flags As SetWindowPosFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWinPosInfo As IntPtr
Dim hWnd As IntPtr
Dim hWndInsertAfter As IntPtr
Dim x As Integer
Dim y As Integer
Dim width As Integer
Dim heigth As Integer
Dim flags As SetWindowPosFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.DeferWindowPos(hWinPosInfo, 
	hWnd, hWndInsertAfter, x, y, width, 
	heigth, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr DeferWindowPos(
	IntPtr hWinPosInfo, 
	IntPtr hWnd, 
	IntPtr hWndInsertAfter, 
	int x, 
	int y, 
	int width, 
	int heigth, 
	SetWindowPosFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member DeferWindowPos : 
        hWinPosInfo : IntPtr * 
        hWnd : IntPtr * 
        hWndInsertAfter : IntPtr * 
        x : int * 
        y : int * 
        width : int * 
        heigth : int * 
        flags : SetWindowPosFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWinPosInfo</dt><dd>Type: System.IntPtr<br />A handle to a multiple-window – position structure that contains size and position information for one or more windows. 

 This structure is returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginDeferWindowPos">BeginDeferWindowPos(Int32)</a> or by the most recent call to DeferWindowPos(IntPtr, IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags).</dd><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window for which update information is stored in the structure. 

 All windows in a multiple-window – position structure must have the same parent.</dd><dt>hWndInsertAfter</dt><dd>Type: System.IntPtr<br />A handle to the window that precedes the positioned window in the Z order. 

 This parameter is ignored if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SetWindowPosFlags">IgnoreZOrder</a> flag is set in the *flags* parameter.</dd><dt>x</dt><dd>Type: System.Int32<br />The x-coordinate of the window's upper-left corner.</dd><dt>y</dt><dd>Type: System.Int32<br />The y-coordinate of the window's upper-left corner.</dd><dt>width</dt><dd>Type: System.Int32<br />The window's new width, in pixels.</dd><dt>heigth</dt><dd>Type: System.Int32<br />The window's new height, in pixels.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SetWindowPosFlags">DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags</a><br />Determine how affect the size and position of the window.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-deferwindowpos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-deferwindowpos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />