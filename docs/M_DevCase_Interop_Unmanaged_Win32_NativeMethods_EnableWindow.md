# NativeMethods.EnableWindow Method (IntPtr, Boolean)
 

Enables or disables mouse and keyboard input to the specified window or control. 

 When input is disabled, the window does not receive input such as mouse clicks and key presses. 

 When input is enabled, the window receives all input.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EnableWindow(
	IntPtr hWnd,
	bool enable
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EnableWindow ( 
	hWnd As IntPtr,
	enable As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim enable As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.EnableWindow(hWnd, 
	enable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EnableWindow(
	IntPtr hWnd, 
	bool enable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EnableWindow : 
        hWnd : IntPtr * 
        enable : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be enabled or disabled.</dd><dt>enable</dt><dd>Type: System.Boolean<br />Indicates whether to enable or disable the window. 

 If this parameter is `true` (`True` in Visual Basic), the window is enabled. 

 If the parameter is `false` (`False` in Visual Basic), the window is disabled.</dd></dl>

#### Return Value
Type: Boolean<br />If the the window is enabled, the return value is `true` (`True` in Visual Basic). 

 If the window is not enabled, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646291%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646291%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnableWindow">EnableWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />