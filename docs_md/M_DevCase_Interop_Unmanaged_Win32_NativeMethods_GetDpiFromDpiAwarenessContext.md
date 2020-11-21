# NativeMethods.GetDpiFromDpiAwarenessContext Method 
 

Retrieves the DPI from a given DPI_AWARENESS_CONTEXT handle. 

 This enables you to determine the DPI of a thread without needed to examine a window created within that thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static uint GetDpiFromDpiAwarenessContext(
	IntPtr value
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function GetDpiFromDpiAwarenessContext ( 
	value As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.GetDpiFromDpiAwarenessContext(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static unsigned int GetDpiFromDpiAwarenessContext(
	IntPtr value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member GetDpiFromDpiAwarenessContext : 
        value : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.IntPtr<br />The DPI_AWARENESS_CONTEXT handle to examine.</dd></dl>

#### Return Value
Type: UInt32<br />The DPI value associated with the DPI_AWARENESS_CONTEXT handle.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getdpifromdpiawarenesscontext" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getdpifromdpiawarenesscontext</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />