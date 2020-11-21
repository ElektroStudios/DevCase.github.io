# NativeMethods.GhostWindowFromHungWindow Method 
 

Returns the handle on the window being ghosted. 

 This function is the reciprocal of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HungWindowFromGhostWindow">HungWindowFromGhostWindow(IntPtr)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GhostWindowFromHungWindow(
	IntPtr hWndHung
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GhostWindowFromHungWindow ( 
	hWndHung As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWndHung As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.GhostWindowFromHungWindow(hWndHung)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GhostWindowFromHungWindow(
	IntPtr hWndHung
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GhostWindowFromHungWindow : 
        hWndHung : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWndHung</dt><dd>Type: System.IntPtr<br />The handle of a hung window.</dd></dl>

#### Return Value
Type: IntPtr<br />The handle of the ghost window which shadows *hWndHung*, or Zero on failure.

## Remarks
<a href="http://undoc.airesoft.co.uk/user32.dll/GhostWindowFromHungWindow.php" target="_blank">http://undoc.airesoft.co.uk/user32.dll/GhostWindowFromHungWindow.php</a>

 A ghost window replaces a window that hasn't called Get or PeekMessage for 5 seconds, in other words a hung window. It displays a bitmap of the hung window's client area.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />