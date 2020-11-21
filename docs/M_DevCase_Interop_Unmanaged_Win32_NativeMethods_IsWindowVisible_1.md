# NativeMethods.IsWindowVisible Method (SafeHandle)
 

Determines the visibility state of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool IsWindowVisible(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function IsWindowVisible ( 
	hWnd As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.IsWindowVisible(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool IsWindowVisible(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member IsWindowVisible : 
        hWnd : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window to be tested.</dd></dl>

#### Return Value
Type: Boolean<br />If the specified window, its parent window, its parent's parent window, and so forth, have the `WS_VISIBLE` style, the return value is `true` (`True` in Visual Basic). 

 Otherwise, the return value is `false` (`False` in Visual Basic). 

 Because the return value specifies whether the window has the WS_VISIBLE style, it may be nonzero even if the window is totally obscured by other windows.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633530%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633530%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsWindowVisible">IsWindowVisible Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />