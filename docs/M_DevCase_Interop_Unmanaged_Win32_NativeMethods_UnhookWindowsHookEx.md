# NativeMethods.UnhookWindowsHookEx Method 
 

Removes a hook procedure installed in a hook chain by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowsHookEx">SetWindowsHookEx(HookType, Delegates.HookProc, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool UnhookWindowsHookEx(
	IntPtr hhk
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function UnhookWindowsHookEx ( 
	hhk As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hhk As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.UnhookWindowsHookEx(hhk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool UnhookWindowsHookEx(
	IntPtr hhk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member UnhookWindowsHookEx : 
        hhk : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hhk</dt><dd>Type: System.IntPtr<br />A handle to the hook to be removed. 

 This parameter is a hook handle obtained by a previous call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowsHookEx">SetWindowsHookEx(HookType, Delegates.HookProc, IntPtr, UInt32)</a>.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644993%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644993%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />