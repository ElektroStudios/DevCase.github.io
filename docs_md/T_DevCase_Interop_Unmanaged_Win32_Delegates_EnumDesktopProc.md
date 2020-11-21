# Delegates.EnumDesktopProc Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktops">EnumDesktops(IntPtr, Delegates.EnumDesktopProc, IntPtr)</a> function. It receives a desktop name. 

 The DESKTOPENUMPROC type defines a pointer to this callback function. 

Delegates.EnumDesktopProc is a placeholder for the application-defined function name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumDesktopProc(
	string desktop,
	IntPtr lParam
)
```

**VB**<br />
``` VB
Public Delegate Function EnumDesktopProc ( 
	desktop As String,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumDesktopProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumDesktopProc(
	String^ desktop, 
	[InAttribute] IntPtr lParam
)
```

**F#**<br />
``` F#
type EnumDesktopProc = 
    delegate of 
        desktop : string * 
        lParam : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>desktop</dt><dd>Type: System.String<br />The name of the desktop.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value specified in the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktops">EnumDesktops(IntPtr, Delegates.EnumDesktopProc, IntPtr)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic). To stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/ms682612(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/ms682612(v=vs.85)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />