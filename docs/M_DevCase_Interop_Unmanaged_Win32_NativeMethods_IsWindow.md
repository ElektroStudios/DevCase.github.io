# NativeMethods.IsWindow Method (IntPtr)
 

Determines whether the specified window handle identifies an existing window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool IsWindow(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function IsWindow ( 
	hWnd As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.IsWindow(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool IsWindow(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member IsWindow : 
        hWnd : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window to be tested.</dd></dl>

#### Return Value
Type: Boolean<br />If the window handle identifies an existing window, the return value is `true` (`True` in Visual Basic). 

 If the window handle does not identify an existing window, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633528%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633528%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsWindow">IsWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />