# NativeMethods.UnregisterHotKey Method (SafeHandle, Int32)
 

Unregisters a hotkey previously registered with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegisterHotKey">RegisterHotKey(IntPtr, Int32, UInt32, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool UnregisterHotKey(
	SafeHandle hWnd,
	int id
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function UnregisterHotKey ( 
	hWnd As SafeHandle,
	id As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim id As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.UnregisterHotKey(hWnd, 
	id)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool UnregisterHotKey(
	SafeHandle^ hWnd, 
	int id
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member UnregisterHotKey : 
        hWnd : SafeHandle * 
        id : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window associated with the hot key to be freed. 

 This parameter should be Zero if the hot key is not associated with a window.</dd><dt>id</dt><dd>Type: System.Int32<br />The identifier of the hotkey to be unregistered.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646327%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646327%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_UnregisterHotKey">UnregisterHotKey Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />