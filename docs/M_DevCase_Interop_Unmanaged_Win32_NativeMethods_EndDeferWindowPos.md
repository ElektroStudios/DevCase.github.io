# NativeMethods.EndDeferWindowPos Method 
 

Simultaneously updates the position and size of one or more windows in a single screen-refreshing cycle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool EndDeferWindowPos(
	IntPtr hWinPosInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function EndDeferWindowPos ( 
	hWinPosInfo As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWinPosInfo As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EndDeferWindowPos(hWinPosInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool EndDeferWindowPos(
	IntPtr hWinPosInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member EndDeferWindowPos : 
        hWinPosInfo : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWinPosInfo</dt><dd>Type: System.IntPtr<br />A handle to a multiple-window – position structure that contains size and position information for one or more windows. 

 This internal structure is returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginDeferWindowPos">BeginDeferWindowPos(Int32)</a> function or by the most recent call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeferWindowPos">DeferWindowPos(IntPtr, IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enddeferwindowpos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enddeferwindowpos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />