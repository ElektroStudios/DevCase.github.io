# NativeMethods.GetThreadDpiAwarenessContext Method 
 

Gets the DPI_AWARENESS_CONTEXT for the current thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr GetThreadDpiAwarenessContext()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetThreadDpiAwarenessContext As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetThreadDpiAwarenessContext()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr GetThreadDpiAwarenessContext()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetThreadDpiAwarenessContext : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The current DPI_AWARENESS_CONTEXT for the thread.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getthreaddpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getthreaddpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />