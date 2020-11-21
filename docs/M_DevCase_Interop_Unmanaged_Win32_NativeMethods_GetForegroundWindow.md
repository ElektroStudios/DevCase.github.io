# NativeMethods.GetForegroundWindow Method 
 

Retrieves a handle to the foreground window (the window with which the user is currently working). 

 The system assigns a slightly higher priority to the thread that creates the foreground window than it does to other threads.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr GetForegroundWindow()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetForegroundWindow As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetForegroundWindow()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr GetForegroundWindow()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetForegroundWindow : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The return value is a handle to the foreground window. 

 The foreground window can be Zero in certain circumstances, such as when a window is losing activation.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633505%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633505%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />