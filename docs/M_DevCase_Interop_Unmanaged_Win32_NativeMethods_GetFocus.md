# NativeMethods.GetFocus Method 
 

Retrieves the handle to the window that has the keyboard focus, if the window is attached to the calling thread's message queue..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr GetFocus()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetFocus As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetFocus()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr GetFocus()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetFocus : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The return value is the handle to the window with the keyboard focus. 

 If the calling thread's message queue does not have an associated window with the keyboard focus, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getfocus" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getfocus</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />