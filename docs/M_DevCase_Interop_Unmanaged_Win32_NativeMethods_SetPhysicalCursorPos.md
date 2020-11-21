# NativeMethods.SetPhysicalCursorPos Method 
 

Sets the position of the cursor in physical coordinates.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetPhysicalCursorPos(
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetPhysicalCursorPos ( 
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.SetPhysicalCursorPos(x, 
	y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetPhysicalCursorPos(
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetPhysicalCursorPos : 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The new x-coordinate of the cursor, in physical coordinates.</dd><dt>y</dt><dd>Type: System.Int32<br />The new y-coordinate of the cursor, in physical coordinates.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setphysicalcursorpos" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setphysicalcursorpos</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />