# NativeMethods.EmptyClipboard Method 
 

Empties the clipboard and frees handles to data in the clipboard. 

 The function then assigns ownership of the clipboard to the window that currently has the clipboard open.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool EmptyClipboard()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function EmptyClipboard As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.EmptyClipboard()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool EmptyClipboard()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member EmptyClipboard : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-emptyclipboard" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-emptyclipboard</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />