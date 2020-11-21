# NativeMethods.GetWindowLongPtr Method (SafeHandle, WindowLongValues)
 

Retrieves information about the specified window. 

 The function also retrieves the value at a specified offset into the extra window memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetWindowLongPtr(
	SafeHandle hWnd,
	WindowLongValues value
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetWindowLongPtr ( 
	hWnd As SafeHandle,
	value As WindowLongValues
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim value As WindowLongValues
Dim returnValue As IntPtr

returnValue = NativeMethods.GetWindowLongPtr(hWnd, 
	value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetWindowLongPtr(
	SafeHandle^ hWnd, 
	WindowLongValues value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetWindowLongPtr : 
        hWnd : SafeHandle * 
        value : WindowLongValues -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window and, indirectly, the class to which the window belongs.</dd><dt>value</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowLongValues">DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues</a><br />The value to be retrieved.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the requested value. 

 If the function fails, the return value is Zero. 

 If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLongPtr">SetWindowLongPtr(IntPtr, WindowLongValues, IntPtr)</a> has not been called previously, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowLongPtr">GetWindowLongPtr(IntPtr, WindowLongValues)</a> returns Zero for values in the extra window or class memory. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633585%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633585%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowLongPtr">GetWindowLongPtr Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />