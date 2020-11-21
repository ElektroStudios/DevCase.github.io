# NativeMethods.BringWindowToTop Method (SafeHandle)
 

Brings the specified window to the top of the Z order. If the window is a top-level window, it is activated. 

 If the window is a child window, the top-level parent window associated with the child window is activated.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool BringWindowToTop(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function BringWindowToTop ( 
	hWnd As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.BringWindowToTop(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool BringWindowToTop(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member BringWindowToTop : 
        hWnd : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to bring to the top of the Z order.</dd></dl>

#### Return Value
Type: Boolean<br />If the the window is zoomed, the return value is `true` (`True` in Visual Basic). 

 If the window is not zoomed, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632673%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632673%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_BringWindowToTop">BringWindowToTop Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />