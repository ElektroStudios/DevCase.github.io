# NativeMethods.GetDpiForWindow Method 
 

Returns the dots per inch (dpi) value for the associated window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static uint GetDpiForWindow(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetDpiForWindow ( 
	hWnd As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As UInteger

returnValue = NativeMethods.GetDpiForWindow(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int GetDpiForWindow(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetDpiForWindow : 
        hWnd : IntPtr -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The window you want to get information about.</dd></dl>

#### Return Value
Type: UInt32<br />The DPI for the window which depends on the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DpiAwareness">DpiAwareness</a> of the window. 

 An invalid *hWnd* value will result in a return value of 0.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getdpiforwindow" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getdpiforwindow</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />