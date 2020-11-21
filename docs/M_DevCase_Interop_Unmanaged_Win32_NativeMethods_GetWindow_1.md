# NativeMethods.GetWindow Method (SafeHandle, GetWindowCmd)
 

Retrieves a handle to a window that has the specified relationship (Z-Order or owner) to the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetWindow(
	SafeHandle hWnd,
	GetWindowCmd gwCmd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindow ( 
	hWnd As SafeHandle,
	gwCmd As GetWindowCmd
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim gwCmd As GetWindowCmd
Dim returnValue As IntPtr

returnValue = NativeMethods.GetWindow(hWnd, 
	gwCmd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetWindow(
	SafeHandle^ hWnd, 
	GetWindowCmd gwCmd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindow : 
        hWnd : SafeHandle * 
        gwCmd : GetWindowCmd -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a window. 

 The window handle retrieved is relative to this window, based on the value of the uCmd parameter.</dd><dt>gwCmd</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetWindowCmd">DevCase.Interop.Unmanaged.Win32.Enums.GetWindowCmd</a><br />The relationship between the specified window and the window whose handle is to be retrieved.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a window handle. 

 If no window exists with the specified relationship to the specified window, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633515%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633515%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindow">GetWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />