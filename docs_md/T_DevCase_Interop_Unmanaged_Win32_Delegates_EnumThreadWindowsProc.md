# Delegates.EnumThreadWindowsProc Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumThreadWindows">EnumThreadWindows(UInt32, Delegates.EnumThreadWindowsProc, IntPtr)</a> function. 

 It receives the window handles associated with a thread. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

Delegates.EnumThreadWindowsProc is a placeholder for the application-defined function name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumThreadWindowsProc(
	IntPtr hWnd,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function EnumThreadWindowsProc ( 
	hWnd As IntPtr,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumThreadWindowsProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumThreadWindowsProc(
	IntPtr hWnd, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
type EnumThreadWindowsProc = 
    delegate of 
        hWnd : IntPtr * 
        lParam : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to a window associated with the thread specified in the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumThreadWindows">EnumThreadWindows(UInt32, Delegates.EnumThreadWindowsProc, IntPtr)</a> function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />The application-defined value given in <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumThreadWindows">EnumThreadWindows(UInt32, Delegates.EnumThreadWindowsProc, IntPtr)</a> functions.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic); to stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633496%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633496%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />