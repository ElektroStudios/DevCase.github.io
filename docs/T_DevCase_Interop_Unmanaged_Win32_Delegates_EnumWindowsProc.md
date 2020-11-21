# Delegates.EnumWindowsProc Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumWindows">EnumWindows(Delegates.EnumWindowsProc, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktopWindows">EnumDesktopWindows(IntPtr, Delegates.EnumWindowsProc, IntPtr)</a> function. 

 It receives top-level window handles. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

Delegates.EnumWindowsProc is a placeholder for the application-defined function name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumWindowsProc(
	IntPtr hWnd,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function EnumWindowsProc ( 
	hWnd As IntPtr,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumWindowsProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumWindowsProc(
	IntPtr hWnd, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
type EnumWindowsProc = 
    delegate of 
        hWnd : IntPtr * 
        lParam : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to a top-level window.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />The application-defined value given in <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumWindows">EnumWindows(Delegates.EnumWindowsProc, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktopWindows">EnumDesktopWindows(IntPtr, Delegates.EnumWindowsProc, IntPtr)</a> functions.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic); to stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633498%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633498%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />