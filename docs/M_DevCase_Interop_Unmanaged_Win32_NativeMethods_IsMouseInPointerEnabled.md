# NativeMethods.IsMouseInPointerEnabled Method 
 

Indicates whether <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnableMouseInPointer">EnableMouseInPointer(Boolean)</a> is set for the mouse to act as a pointer input device and send WM_POINTER* messages.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool IsMouseInPointerEnabled()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function IsMouseInPointerEnabled As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.IsMouseInPointerEnabled()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool IsMouseInPointerEnabled()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member IsMouseInPointerEnabled : unit -> bool 

```


#### Return Value
Type: Boolean<br />If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnableMouseInPointer">EnableMouseInPointer(Boolean)</a> is set, the return value is `true` (`True` in Visual Basic). 

 If <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnableMouseInPointer">EnableMouseInPointer(Boolean)</a> is not set, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-ismouseinpointerenabled" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-ismouseinpointerenabled</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />