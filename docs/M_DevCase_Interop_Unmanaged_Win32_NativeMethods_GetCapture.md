# NativeMethods.GetCapture Method 
 

Retrieves a handle to the window (if any) that has captured the mouse. 

 Only one window at a time can capture the mouse; this window receives mouse input whether or not the cursor is within its borders.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr GetCapture()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetCapture As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetCapture()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr GetCapture()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetCapture : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The return value is a handle to the capture window associated with the current thread. 

 If no window in the thread has captured the mouse, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getcapture" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getcapture</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />