# NativeMethods.SetProcessDpiAwarenessContext Method 
 

Sets the current process to a specified dots per inch (dpi) awareness context. 

 The DPI awareness contexts are from the DPI_AWARENESS_CONTEXT value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetProcessDpiAwarenessContext(
	IntPtr value
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetProcessDpiAwarenessContext ( 
	value As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessDpiAwarenessContext(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetProcessDpiAwarenessContext(
	IntPtr value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetProcessDpiAwarenessContext : 
        value : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.IntPtr<br />A DPI_AWARENESS_CONTEXT handle to set.</dd></dl>

#### Return Value
Type: Boolean<br />This function returns `true` (`True` in Visual Basic) if the operation was successful, and `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setprocessdpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setprocessdpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />