# NativeMethods.SwitchToThisWindow Method (IntPtr, Boolean)
 

Switches focus to the specified window and brings it to the foreground.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SwitchToThisWindow(
	IntPtr hWnd,
	bool altTab
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SwitchToThisWindow ( 
	hWnd As IntPtr,
	altTab As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim altTab As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SwitchToThisWindow(hWnd, 
	altTab)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SwitchToThisWindow(
	IntPtr hWnd, 
	bool altTab
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SwitchToThisWindow : 
        hWnd : IntPtr * 
        altTab : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd><dt>altTab</dt><dd>Type: System.Boolean<br />A `true` (`True` in Visual Basic) for this parameter indicates that the window is being switched to using the `Alt+Tab` key sequence. 

 This parameter should be `false` (`False` in Visual Basic) otherwise.</dd></dl>

#### Return Value
Type: Boolean<br />If the the window is enabled, the return value is `true` (`True` in Visual Basic). 

 If the window is not enabled, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633553%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633553%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SwitchToThisWindow">SwitchToThisWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />