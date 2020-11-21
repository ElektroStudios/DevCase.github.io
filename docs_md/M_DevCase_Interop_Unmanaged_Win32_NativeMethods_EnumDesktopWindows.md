# NativeMethods.EnumDesktopWindows Method 
 

Enumerates all top-level windows associated with the specified desktop. 

 It passes the handle to each window, in turn, to an application-defined callback function

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EnumDesktopWindows(
	IntPtr hDesktop,
	Delegates.EnumWindowsProc lpEnumFunc,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EnumDesktopWindows ( 
	hDesktop As IntPtr,
	lpEnumFunc As Delegates.EnumWindowsProc,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDesktop As IntPtr
Dim lpEnumFunc As Delegates.EnumWindowsProc
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumDesktopWindows(hDesktop, 
	lpEnumFunc, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EnumDesktopWindows(
	IntPtr hDesktop, 
	Delegates.EnumWindowsProc^ lpEnumFunc, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EnumDesktopWindows : 
        hDesktop : IntPtr * 
        lpEnumFunc : Delegates.EnumWindowsProc * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDesktop</dt><dd>Type: System.IntPtr<br />A handle to the desktop whose top-level windows are to be enumerated. 

 This handle is returned by the `CreateDesktop`, `GetThreadDesktop`, `OpenDesktop`, or `OpenInputDesktop` function, and must have the `DESKTOP_READOBJECTS` access right.</dd><dt>lpEnumFunc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumWindowsProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumWindowsProc</a><br />A pointer to an application-defined callback function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value to be passed to the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />if the function succeeds, the return value is`true` (`True` in Visual Basic). 

 If the function fails or is unable to perform the enumeration, the return value is`false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms682615%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms682615%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />