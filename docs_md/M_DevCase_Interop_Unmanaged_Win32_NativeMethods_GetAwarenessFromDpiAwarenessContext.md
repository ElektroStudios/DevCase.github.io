# NativeMethods.GetAwarenessFromDpiAwarenessContext Method 
 

Retrieves the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">DpiAwareness</a> value from a DPI_AWARENESS_CONTEXT.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static DpiAwareness GetAwarenessFromDpiAwarenessContext(
	IntPtr value
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetAwarenessFromDpiAwarenessContext ( 
	value As IntPtr
) As DpiAwareness
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr
Dim returnValue As DpiAwareness

returnValue = NativeMethods.GetAwarenessFromDpiAwarenessContext(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static DpiAwareness GetAwarenessFromDpiAwarenessContext(
	IntPtr value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetAwarenessFromDpiAwarenessContext : 
        value : IntPtr -> DpiAwareness 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.IntPtr<br />The DPI_AWARENESS_CONTEXT you want to examine.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">DpiAwareness</a><br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">DpiAwareness</a>. 

 If the provided value is null or invalid, this method will return <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">Invalid</a>.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getawarenessfromdpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getawarenessfromdpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />