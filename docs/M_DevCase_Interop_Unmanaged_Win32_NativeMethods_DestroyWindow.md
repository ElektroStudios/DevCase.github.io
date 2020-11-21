# NativeMethods.DestroyWindow Method (IntPtr)
 

Destroys the specified window. The function sends <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Destroy</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcDestroy</a> messages to the window to deactivate it and remove the keyboard focus from it. 

 The function also destroys the window's menu, flushes the thread message queue, destroys timers, removes clipboard ownership, and breaks the clipboard viewer chain (if the window is at the top of the viewer chain). 

 If the specified window is a parent or owner window, DestroyWindow(IntPtr) automatically destroys the associated child or owned windows when it destroys the parent or owner window. 

 The function first destroys child or owned windows, and then it destroys the parent or owner window. 

DestroyWindow(IntPtr) also destroys modeless dialog boxes created by the `CreateDialog` function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	SetLastError = true)]
public static IntPtr DestroyWindow(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CallingConvention := CallingConvention.StdCall, 
	SetLastError := true>]
Public Shared Function DestroyWindow ( 
	hWnd As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DestroyWindow(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CallingConvention = CallingConvention::StdCall, 
	SetLastError = true)]
static IntPtr DestroyWindow(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CallingConvention = CallingConvention.StdCall, 
	SetLastError = true)>]
static member DestroyWindow : 
        hWnd : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be destroyed.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is Zero. 

 If the function fails, the return value is equal to a handle to the local memory object. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632682%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632682%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />