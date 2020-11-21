# NativeMethods.CloseWindowStation Method 
 

Closes an open window station handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool CloseWindowStation(
	IntPtr hWinsta
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function CloseWindowStation ( 
	hWinsta As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWinsta As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.CloseWindowStation(hWinsta)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool CloseWindowStation(
	IntPtr hWinsta
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member CloseWindowStation : 
        hWinsta : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWinsta</dt><dd>Type: System.IntPtr<br />A handle to the window station to be closed. This handle is returned by the CreateWindowStation or OpenWindowStation function. 

 Do not specify the handle returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcessWindowStation">GetProcessWindowStation()</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-closewindowstation" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-closewindowstation</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />