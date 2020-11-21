# NativeMethods.SetWindowLongPtr Method (SafeHandle, WindowLongValues, IntPtr)
 

Changes an attribute of the specified window. 

 The function also sets a value at the specified offset in the extra window memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr SetWindowLongPtr(
	SafeHandle hWnd,
	WindowLongValues value,
	IntPtr newValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetWindowLongPtr ( 
	hWnd As SafeHandle,
	value As WindowLongValues,
	newValue As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim value As WindowLongValues
Dim newValue As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetWindowLongPtr(hWnd, 
	value, newValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr SetWindowLongPtr(
	SafeHandle^ hWnd, 
	WindowLongValues value, 
	IntPtr newValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetWindowLongPtr : 
        hWnd : SafeHandle * 
        value : WindowLongValues * 
        newValue : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window and, indirectly, the class to which the window belongs. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLongPtr">SetWindowLongPtr(IntPtr, WindowLongValues, IntPtr)</a> function fails if the process that owns the window specified by the *hWnd* parameter is at a higher process privilege in the `UIPI` hierarchy than the process the calling thread resides in.</dd><dt>value</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowLongValues">DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues</a><br />The value to be set.</dd><dt>newValue</dt><dd>Type: System.IntPtr<br />The replacement value.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the previous value of the specified offset. 

 If the function fails, the return value is Zero. 

 If the previous value is Zero and the function succeeds, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644898%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644898%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLongPtr">SetWindowLongPtr Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />