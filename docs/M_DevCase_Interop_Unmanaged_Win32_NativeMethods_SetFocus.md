# NativeMethods.SetFocus Method 
 

Sets the keyboard focus to the specified window. 

 The window must be attached to the calling thread's message queue.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr SetFocus(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetFocus ( 
	hWnd As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetFocus(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr SetFocus(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetFocus : 
        hWnd : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window that will receive the keyboard input. 

 If this parameter is Zero, keystrokes are ignored.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the window that previously had the keyboard focus. 

 If the *hWnd* parameter is invalid or the window is not attached to the calling thread's message queue, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646312(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646312(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />