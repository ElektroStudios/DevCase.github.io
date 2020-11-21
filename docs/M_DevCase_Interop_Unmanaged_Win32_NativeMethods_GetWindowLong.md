# NativeMethods.GetWindowLong Method (IntPtr, WindowLongValues)
 

**Note: This API is now obsolete.**

Retrieves information about the specified window. 

 The function also retrieves the 32-bit (`DWORD`) value at the specified offset into the extra window memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
[ObsoleteAttribute]
public static uint GetWindowLong(
	IntPtr hWnd,
	WindowLongValues flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
<ObsoleteAttribute>
Public Shared Function GetWindowLong ( 
	hWnd As IntPtr,
	flags As WindowLongValues
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim flags As WindowLongValues
Dim returnValue As UInteger

returnValue = NativeMethods.GetWindowLong(hWnd, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
[ObsoleteAttribute]
static unsigned int GetWindowLong(
	IntPtr hWnd, 
	WindowLongValues flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
[<ObsoleteAttribute>]
static member GetWindowLong : 
        hWnd : IntPtr * 
        flags : WindowLongValues -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window and, indirectly, the class to which the window belongs.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowLongValues">DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues</a><br />The zero-based offset to the value to be retrieved. 

 Valid values are in the range zero through the number of bytes of extra window memory, minus the size of an integer.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the requested value. 

 If the function fails, the return value is zero. 

 If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLong">SetWindowLong(IntPtr, WindowLongValues, UInt32)</a> has not been called previously, GetWindowLong(IntPtr, WindowLongValues) returns zero for values in the extra window or class memory. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633584%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633584%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowLong">GetWindowLong Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />