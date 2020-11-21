# NativeMethods.GetDesktopWindow Method 
 

Retrieves a handle to the desktop window. 

 The desktop window is the area on top of which other windows are painted.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static IntPtr GetDesktopWindow()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetDesktopWindow As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetDesktopWindow()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static IntPtr GetDesktopWindow()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetDesktopWindow : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />A IntPtr handle to the desktop window.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633504%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633504%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />