# NativeMethods.EndTask Method 
 

Forcibly closes the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EndTask(
	IntPtr hWnd,
	bool shutDown,
	bool force
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EndTask ( 
	hWnd As IntPtr,
	shutDown As Boolean,
	force As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim shutDown As Boolean
Dim force As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.EndTask(hWnd, 
	shutDown, force)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EndTask(
	IntPtr hWnd, 
	bool shutDown, 
	bool force
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EndTask : 
        hWnd : IntPtr * 
        shutDown : bool * 
        force : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be closed.</dd><dt>shutDown</dt><dd>Type: System.Boolean<br />Ignored. Must be `false` (`False` in Visual Basic).</dd><dt>force</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), EndTask(IntPtr, Boolean, Boolean) will force the destruction of the window if an initial attempt fails to gently close the window using <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Close</a> message. 

 If of `false` (`False` in Visual Basic), only the close with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Close</a> message is attempted.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-endtask" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-endtask</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />