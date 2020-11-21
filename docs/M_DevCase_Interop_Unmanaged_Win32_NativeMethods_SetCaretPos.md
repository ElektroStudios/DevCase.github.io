# NativeMethods.SetCaretPos Method 
 

Moves the caret to the specified coordinates. 

 If the window that owns the caret was created with the `CS_OWNDC` class style, then the specified coordinates are subject to the mapping mode of the device context associated with that window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetCaretPos(
	int x,
	int y
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetCaretPos ( 
	x As Integer,
	y As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim x As Integer
Dim y As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.SetCaretPos(x, 
	y)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetCaretPos(
	int x, 
	int y
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetCaretPos : 
        x : int * 
        y : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>x</dt><dd>Type: System.Int32<br />The new x-coordinate of the caret.</dd><dt>y</dt><dd>Type: System.Int32<br />The new y-coordinate of the caret.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648405%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648405%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />