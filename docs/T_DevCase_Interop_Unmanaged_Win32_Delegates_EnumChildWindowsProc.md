# Delegates.EnumChildWindowsProc Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr)</a> function. 

 It receives the child window handles. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

Delegates.EnumChildWindowsProc is a placeholder for the application-defined function name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumChildWindowsProc(
	IntPtr hWnd,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function EnumChildWindowsProc ( 
	hWnd As IntPtr,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumChildWindowsProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumChildWindowsProc(
	IntPtr hWnd, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
type EnumChildWindowsProc = 
    delegate of 
        hWnd : IntPtr * 
        lParam : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to a child window of the parent window specified in <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr)</a> function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />The application-defined value given in <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic); to stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633493%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633493%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />