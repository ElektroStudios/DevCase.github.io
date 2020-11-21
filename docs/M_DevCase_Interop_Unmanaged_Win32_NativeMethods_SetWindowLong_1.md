# NativeMethods.SetWindowLong Method (SafeHandle, WindowLongValues, UInt32)
 

**Note: This API is now obsolete.**

Changes an attribute of the specified window. 

 The function also sets the 32-bit (`LONG`) value at the specified offset into the extra window memory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
[ObsoleteAttribute]
public static uint SetWindowLong(
	SafeHandle hWnd,
	WindowLongValues flags,
	uint newLong
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
<ObsoleteAttribute>
Public Shared Function SetWindowLong ( 
	hWnd As SafeHandle,
	flags As WindowLongValues,
	newLong As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim flags As WindowLongValues
Dim newLong As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.SetWindowLong(hWnd, 
	flags, newLong)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
[ObsoleteAttribute]
static unsigned int SetWindowLong(
	SafeHandle^ hWnd, 
	WindowLongValues flags, 
	unsigned int newLong
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
[<ObsoleteAttribute>]
static member SetWindowLong : 
        hWnd : SafeHandle * 
        flags : WindowLongValues * 
        newLong : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window and, indirectly, the class to which the window belongs.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowLongValues">DevCase.Interop.Unmanaged.Win32.Enums.WindowLongValues</a><br />The zero-based offset to the value to be set. 

 Valid values are in the range zero through the number of bytes of extra window memory, minus the size of an integer.</dd><dt>newLong</dt><dd>Type: System.UInt32<br />The replacement value.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the previous value of the specified 32-bit integer. 

 If the function fails, the return value is zero. 

 If the previous value of the specified 32-bit integer is zero, and the function succeeds, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633591%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633591%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowLong">SetWindowLong Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />