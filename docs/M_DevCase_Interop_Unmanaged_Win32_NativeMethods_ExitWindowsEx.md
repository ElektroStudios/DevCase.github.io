# NativeMethods.ExitWindowsEx Method 
 

Logs off the interactive user, shuts down the system, or shuts down and restarts the system. 

 It sends the `WM_QUERYENDSESSION` message to all applications to determine if they can be terminated.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ExitWindowsEx(
	ExitwindowsExFlags flags,
	ShutdownReason reason
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ExitWindowsEx ( 
	flags As ExitwindowsExFlags,
	reason As ShutdownReason
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As ExitwindowsExFlags
Dim reason As ShutdownReason
Dim returnValue As Boolean

returnValue = NativeMethods.ExitWindowsEx(flags, 
	reason)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ExitWindowsEx(
	ExitwindowsExFlags flags, 
	ShutdownReason reason
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ExitWindowsEx : 
        flags : ExitwindowsExFlags * 
        reason : ShutdownReason -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExitwindowsExFlags">DevCase.Interop.Unmanaged.Win32.Enums.ExitwindowsExFlags</a><br />The shutdown type.</dd><dt>reason</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShutdownReason">DevCase.Interop.Unmanaged.Win32.Enums.ShutdownReason</a><br />The reason for initiating the shutdown.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 The function executes asynchronously so a `true` (`True` in Visual Basic) return value indicates that the shutdown has been initiated. 

 It does not indicate whether the shutdown will succeed. It is possible that the system, the user, or another application will abort the shutdown. 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376868%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376868%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />