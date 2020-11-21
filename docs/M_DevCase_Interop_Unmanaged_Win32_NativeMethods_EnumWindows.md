# NativeMethods.EnumWindows Method 
 

Enumerates all top-level windows on the screen by passing the handle to each window, in turn, to an application-defined callback function. 

EnumWindows(Delegates.EnumWindowsProc, IntPtr) continues until the last top-level window is enumerated or the callback function returns `false` (`False` in Visual Basic).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EnumWindows(
	Delegates.EnumWindowsProc lpEnumFunc,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EnumWindows ( 
	lpEnumFunc As Delegates.EnumWindowsProc,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim lpEnumFunc As Delegates.EnumWindowsProc
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumWindows(lpEnumFunc, 
	lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EnumWindows(
	Delegates.EnumWindowsProc^ lpEnumFunc, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EnumWindows : 
        lpEnumFunc : Delegates.EnumWindowsProc * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>lpEnumFunc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumWindowsProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumWindowsProc</a><br />A pointer to an application-defined callback function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value to be passed to the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise. 

 If `EnumWindowsProc` returns `false` (`False` in Visual Basic), the return value is also `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633497%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633497%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />