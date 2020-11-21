# NativeMethods.LockWindowUpdate Method 
 

Disables or enables drawing in the specified window. Only one window can be locked at a time.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool LockWindowUpdate(
	IntPtr hWndLock
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function LockWindowUpdate ( 
	hWndLock As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWndLock As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.LockWindowUpdate(hWndLock)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool LockWindowUpdate(
	IntPtr hWndLock
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member LockWindowUpdate : 
        hWndLock : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWndLock</dt><dd>Type: System.IntPtr<br />The window in which drawing will be disabled. 

 If this parameter is Zero, drawing in the locked window is enabled.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic), indicating that an error occurred or another window was already locked. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-lockwindowupdate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-lockwindowupdate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />