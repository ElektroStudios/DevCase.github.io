# NativeMethods.AnyPopup Method 
 

**Note: This API is now obsolete.**

Indicates whether an owned, visible, top-level pop-up, or overlapped window exists on the screen. The function searches the entire screen, not just the calling application's client area. 

 This function is provided only for compatibility with 16-bit versions of Windows. It is generally not useful.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
[ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. It is generally not useful.", 
	false)]
public static bool AnyPopup()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
<ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. It is generally not useful.", 
	false)>
Public Shared Function AnyPopup As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.AnyPopup()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
[ObsoleteAttribute(L"This function is provided only for compatibility with 16-bit versions of Windows. It is generally not useful.", 
	false)]
static bool AnyPopup()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
[<ObsoleteAttribute("This function is provided only for compatibility with 16-bit versions of Windows. It is generally not useful.", 
	false)>]
static member AnyPopup : unit -> bool 

```


#### Return Value
Type: Boolean<br />If a pop-up window exists, the return value is `true` (`True` in Visual Basic), even if the pop-up window is completely covered by other windows. 

 If a pop-up window does not exist, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-anypopup" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-anypopup</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />