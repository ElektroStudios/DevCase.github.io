# NativeMethods.HungWindowFromGhostWindow Method 
 

Returns the handle on the window being ghosted. 

 This function is the reciprocal of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GhostWindowFromHungWindow">GhostWindowFromHungWindow(IntPtr)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr HungWindowFromGhostWindow(
	IntPtr hWndGhost
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function HungWindowFromGhostWindow ( 
	hWndGhost As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWndGhost As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.HungWindowFromGhostWindow(hWndGhost)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr HungWindowFromGhostWindow(
	IntPtr hWndGhost
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member HungWindowFromGhostWindow : 
        hWndGhost : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWndGhost</dt><dd>Type: System.IntPtr<br />The handle of a ghost window.</dd></dl>

#### Return Value
Type: IntPtr<br />The handle of the hung window which shadows *hWndGhost*, or Zero on failure.

## Remarks
<a href="http://undoc.airesoft.co.uk/user32.dll/HungWindowFromGhostWindow.php" target="_blank">http://undoc.airesoft.co.uk/user32.dll/HungWindowFromGhostWindow.php</a>

 Ghost windows have a window class of "Ghost". Details of their window class can be gotten by calling: `GetClassInfoEx(NULL, TEXT("Ghost"))`

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />