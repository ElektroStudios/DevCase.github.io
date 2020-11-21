# NativeMethods.GetCaretBlinkTime Method 
 

Retrieves the time required to invert the caret's pixels. The user can set this value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetCaretBlinkTime()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetCaretBlinkTime As Integer
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Integer

returnValue = NativeMethods.GetCaretBlinkTime()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetCaretBlinkTime()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetCaretBlinkTime : unit -> int 

```


#### Return Value
Type: Int32<br />If the function succeeds, the return value is the blink time, in milliseconds. 

 A return value of INFINITE indicates that the caret does not blink. 

 A return value is zero indicates that the function has failed.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getcaretblinktime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getcaretblinktime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />