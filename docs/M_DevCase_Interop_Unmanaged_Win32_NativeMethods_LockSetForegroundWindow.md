# NativeMethods.LockSetForegroundWindow Method 
 

The foreground process can call this function to disable calls to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetForegroundWindow">SetForegroundWindow(IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool LockSetForegroundWindow(
	SetForegroundWindowLockModes lockMode
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function LockSetForegroundWindow ( 
	lockMode As SetForegroundWindowLockModes
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim lockMode As SetForegroundWindowLockModes
Dim returnValue As Boolean

returnValue = NativeMethods.LockSetForegroundWindow(lockMode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool LockSetForegroundWindow(
	SetForegroundWindowLockModes lockMode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member LockSetForegroundWindow : 
        lockMode : SetForegroundWindowLockModes -> bool 

```


#### Parameters
&nbsp;<dl><dt>lockMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SetForegroundWindowLockModes">DevCase.Interop.Unmanaged.Win32.Enums.SetForegroundWindowLockModes</a><br />Specifies whether to enable or disable calls to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetForegroundWindow">SetForegroundWindow(IntPtr)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633532%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633532%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />