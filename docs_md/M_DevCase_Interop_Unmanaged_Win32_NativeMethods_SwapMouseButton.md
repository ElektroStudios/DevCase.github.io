# NativeMethods.SwapMouseButton Method 
 

Reverses or restores the meaning of the left and right mouse buttons.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool SwapMouseButton(
	bool swap
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function SwapMouseButton ( 
	swap As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim swap As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SwapMouseButton(swap)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool SwapMouseButton(
	bool swap
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member SwapMouseButton : 
        swap : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>swap</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the left button generates right-button messages and the right button generates left-button messages. 

 If this parameter is `false` (`False` in Visual Basic), the buttons are restored to their original meanings.</dd></dl>

#### Return Value
Type: Boolean<br />If the meaning of the mouse buttons was reversed previously, before the function was called, the return value is `true` (`True` in Visual Basic). 

 If the meaning of the mouse buttons was not reversed, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-swapmousebutton" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-swapmousebutton</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />