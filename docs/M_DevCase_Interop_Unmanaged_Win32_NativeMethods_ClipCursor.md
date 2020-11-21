# NativeMethods.ClipCursor Method 
 

Confines the cursor to a rectangular area on the screen. 

 If a subsequent cursor position (set by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetCursorPos">SetCursorPos(Int32, Int32)</a> function or the mouse) lies outside the rectangle, the system automatically adjusts the position to keep the cursor inside the rectangular area.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ClipCursor(
	ref NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ClipCursor ( 
	ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.ClipCursor(refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ClipCursor(
	NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ClipCursor : 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> that contains the screen coordinates of the upper-left and lower-right corners of the confining rectangle. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the cursor is free to move anywhere on the screen.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648383(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648383(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />