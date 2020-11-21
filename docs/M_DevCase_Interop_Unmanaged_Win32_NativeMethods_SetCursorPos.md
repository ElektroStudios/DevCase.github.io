# NativeMethods.SetCursorPos Method 
 

Moves the cursor to the specified screen coordinates. 

 If the new coordinates are not within the screen rectangle set by the most recent <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ClipCursor">ClipCursor(NativeRectangle)</a> function call, the system automatically adjusts the coordinates so that the cursor stays within the rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetCursorPos(
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetCursorPos ( 
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.SetCursorPos(x, 
	y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetCursorPos(
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetCursorPos : 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The new x-coordinate of the cursor, in screen coordinates.</dd><dt>y</dt><dd>Type: System.Int32<br />The new y-coordinate of the cursor, in screen coordinates.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648394(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648394(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />