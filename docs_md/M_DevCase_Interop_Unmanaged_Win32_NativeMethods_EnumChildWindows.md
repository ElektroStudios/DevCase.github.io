# NativeMethods.EnumChildWindows Method (IntPtr, Delegates.EnumChildWindowsProc, IntPtr)
 

Enumerates the child windows that belong to the specified parent window by passing the handle to each child window, in turn, to an application-defined callback function. 

EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr) continues until the last child window is enumerated or the callback function returns `false` (`False` in Visual Basic).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EnumChildWindows(
	IntPtr hWndParent,
	Delegates.EnumChildWindowsProc enumFunc,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EnumChildWindows ( 
	hWndParent As IntPtr,
	enumFunc As Delegates.EnumChildWindowsProc,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWndParent As IntPtr
Dim enumFunc As Delegates.EnumChildWindowsProc
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumChildWindows(hWndParent, 
	enumFunc, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EnumChildWindows(
	IntPtr hWndParent, 
	Delegates.EnumChildWindowsProc^ enumFunc, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EnumChildWindows : 
        hWndParent : IntPtr * 
        enumFunc : Delegates.EnumChildWindowsProc * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWndParent</dt><dd>Type: System.IntPtr<br />A handle to the parent window whose child windows are to be enumerated. 

 If this parameter is Zero, this function is equivalent to calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumWindows">EnumWindows(Delegates.EnumWindowsProc, IntPtr)</a> function.</dd><dt>enumFunc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumChildWindowsProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumChildWindowsProc</a><br />A pointer to an application-defined callback function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value to be passed to the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />The return value is not used.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633494%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633494%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />