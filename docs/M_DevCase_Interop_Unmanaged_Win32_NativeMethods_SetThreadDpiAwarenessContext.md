# NativeMethods.SetThreadDpiAwarenessContext Method 
 

Set the DPI awareness for the current thread to the provided value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr SetThreadDpiAwarenessContext(
	IntPtr dpiContext
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function SetThreadDpiAwarenessContext ( 
	dpiContext As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim dpiContext As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetThreadDpiAwarenessContext(dpiContext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr SetThreadDpiAwarenessContext(
	IntPtr dpiContext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member SetThreadDpiAwarenessContext : 
        dpiContext : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>dpiContext</dt><dd>Type: System.IntPtr<br />The new DPI_AWARENESS_CONTEXT for the current thread. This context includes the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">DpiAwareness</a> value.</dd></dl>

#### Return Value
Type: IntPtr<br />The old DPI_AWARENESS_CONTEXT for the thread. 

 If the *dpiContext* is invalid, the thread will not be updated and the return value will be NULL. 

 You can use this value to restore the old DPI_AWARENESS_CONTEXT after overriding it with a predefined value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setthreaddpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setthreaddpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />