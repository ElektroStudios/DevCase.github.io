# NativeMethods.CalculatePopupWindowPosition Method 
 

Calculates an appropriate pop-up window position using the specified anchor point, pop-up window size, flags, and the optional exclude rectangle. 

 When the specified pop-up window size is smaller than the desktop window size, use the CalculatePopupWindowPosition(NativePoint, NativeSize, PopupWindowPositionFlags, NativeRectangle, NativeSize) function to ensure that the pop-up window is fully visible on the desktop window, regardless of the specified anchor point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool CalculatePopupWindowPosition(
	ref NativePoint refAnchorPoint,
	ref NativeSize refWindowSize,
	PopupWindowPositionFlags flags,
	ref NativeRectangle refExcludeRect,
	ref NativeSize refPopupPosition
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CalculatePopupWindowPosition ( 
	ByRef refAnchorPoint As NativePoint,
	ByRef refWindowSize As NativeSize,
	flags As PopupWindowPositionFlags,
	ByRef refExcludeRect As NativeRectangle,
	ByRef refPopupPosition As NativeSize
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refAnchorPoint As NativePoint
Dim refWindowSize As NativeSize
Dim flags As PopupWindowPositionFlags
Dim refExcludeRect As NativeRectangle
Dim refPopupPosition As NativeSize
Dim returnValue As Boolean

returnValue = NativeMethods.CalculatePopupWindowPosition(refAnchorPoint, 
	refWindowSize, flags, refExcludeRect, 
	refPopupPosition)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool CalculatePopupWindowPosition(
	NativePoint% refAnchorPoint, 
	NativeSize% refWindowSize, 
	PopupWindowPositionFlags flags, 
	NativeRectangle% refExcludeRect, 
	NativeSize% refPopupPosition
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CalculatePopupWindowPosition : 
        refAnchorPoint : NativePoint byref * 
        refWindowSize : NativeSize byref * 
        flags : PopupWindowPositionFlags * 
        refExcludeRect : NativeRectangle byref * 
        refPopupPosition : NativeSize byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refAnchorPoint</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that specifies the specified anchor point.</dd><dt>refWindowSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> structure that specifies the specified window size.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PopupWindowPositionFlags">DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags</a><br />Flags that specifies how the function positions the pop-up window horizontally and vertically.</dd><dt>refExcludeRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the exclude rectangle. 

 It can be a null reference (`Nothing` in Visual Basic).</dd><dt>refPopupPosition</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> structure that specifies the pop-up window position.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd565861%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd565861%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />