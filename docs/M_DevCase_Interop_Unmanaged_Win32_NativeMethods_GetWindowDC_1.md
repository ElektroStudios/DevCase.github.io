# NativeMethods.GetWindowDC Method (SafeHandle)
 

Retrieves the device context (DC) for the entire window, including title bar, menus, and scroll bars. 

 A window device context permits painting anywhere in a window, because the origin of the device context is the upper-left corner of the window instead of the client area. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowDC">GetWindowDC(IntPtr)</a> assigns default attributes to the window device context each time it retrieves the device context. Previous attributes are lost.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetWindowDC(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowDC ( 
	hWnd As SafeHandle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As IntPtr

returnValue = NativeMethods.GetWindowDC(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetWindowDC(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowDC : 
        hWnd : SafeHandle -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window with a device context that is to be retrieved. If this value is Zero, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowDC">GetWindowDC(IntPtr)</a> retrieves the device context for the entire screen of the primary display monitor. 

 To get the device context for other display monitors, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateDC">CreateDC(String, String, String, IntPtr)</a> functions.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to a device context for the specified window. 

 If the function fails, the return value is Zero, indicating an error or an invalid *hWnd* parameter.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144947%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144947%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowDC">GetWindowDC Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />