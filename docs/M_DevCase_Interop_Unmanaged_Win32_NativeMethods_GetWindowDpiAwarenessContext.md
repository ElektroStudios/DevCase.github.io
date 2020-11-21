# NativeMethods.GetWindowDpiAwarenessContext Method 
 

Returns the DPI_AWARENESS_CONTEXT associated with a window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr GetWindowDpiAwarenessContext(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetWindowDpiAwarenessContext ( 
	hWnd As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.GetWindowDpiAwarenessContext(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr GetWindowDpiAwarenessContext(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetWindowDpiAwarenessContext : 
        hWnd : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The window to query.</dd></dl>

#### Return Value
Type: IntPtr<br />The DPI_AWARENESS_CONTEXT for the provided window. If the window is not valid, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowdpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getwindowdpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />