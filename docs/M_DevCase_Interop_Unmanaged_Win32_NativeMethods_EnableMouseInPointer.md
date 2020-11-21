# NativeMethods.EnableMouseInPointer Method 
 

Enables the mouse to act as a pointer input device and send WM_POINTER* messages.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool EnableMouseInPointer(
	bool enable
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function EnableMouseInPointer ( 
	enable As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim enable As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.EnableMouseInPointer(enable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool EnableMouseInPointer(
	bool enable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member EnableMouseInPointer : 
        enable : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>enable</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to turn on mouse input support in WM_POINTER* messages.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enablemouseinpointer" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-enablemouseinpointer</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />