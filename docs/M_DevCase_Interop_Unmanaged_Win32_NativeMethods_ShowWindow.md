# NativeMethods.ShowWindow Method (IntPtr, NativeWindowState)
 

Sets the specified window's show state.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ShowWindow(
	IntPtr hWnd,
	NativeWindowState windowState
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ShowWindow ( 
	hWnd As IntPtr,
	windowState As NativeWindowState
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim windowState As NativeWindowState
Dim returnValue As Boolean

returnValue = NativeMethods.ShowWindow(hWnd, 
	windowState)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ShowWindow(
	IntPtr hWnd, 
	NativeWindowState windowState
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ShowWindow : 
        hWnd : IntPtr * 
        windowState : NativeWindowState -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A IntPtr handle to the window.</dd><dt>windowState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState</a><br />Controls how the window is to be shown.</dd></dl>

#### Return Value
Type: Boolean<br />If the window was previously visible, the return value is `true` (`True` in Visual Basic). 

 If the window was previously hidden, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633548%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633548%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />