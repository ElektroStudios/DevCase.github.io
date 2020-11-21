# NativeMethods.GetActiveWindow Method 
 

Retrieves the window handle to the active window attached to the calling thread's message queue.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr GetActiveWindow()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetActiveWindow As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetActiveWindow()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr GetActiveWindow()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetActiveWindow : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The return value is the handle to the active window attached to the calling thread's message queue. Otherwise, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getactivewindow" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getactivewindow</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />