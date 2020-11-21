# NativeMethods.IsValidDpiAwarenessContext Method 
 

Determines if a specified DPI_AWARENESS_CONTEXT is valid and supported by the current system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool IsValidDpiAwarenessContext(
	IntPtr value
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function IsValidDpiAwarenessContext ( 
	value As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.IsValidDpiAwarenessContext(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool IsValidDpiAwarenessContext(
	IntPtr value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member IsValidDpiAwarenessContext : 
        value : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.IntPtr<br />The context that you want to determine if it is supported.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the provided context is supported, otherwise `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-isvaliddpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-isvaliddpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />