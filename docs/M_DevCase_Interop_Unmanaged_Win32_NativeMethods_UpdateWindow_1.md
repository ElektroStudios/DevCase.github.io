# NativeMethods.UpdateWindow Method (SafeHandle)
 

Updates the client area of the specified window by sending a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message to the window if the window's update region is not empty. 

 The function sends a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message directly to the window procedure of the specified window, bypassing the application queue. If the update region is empty, no message is sent.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool UpdateWindow(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function UpdateWindow ( 
	hWnd As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.UpdateWindow(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool UpdateWindow(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member UpdateWindow : 
        hWnd : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to be updated.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-updatewindow" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-updatewindow</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateWindow">UpdateWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />