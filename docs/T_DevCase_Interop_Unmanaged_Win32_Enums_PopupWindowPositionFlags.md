# PopupWindowPositionFlags Enumeration
 

Specifies how the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CalculatePopupWindowPosition">CalculatePopupWindowPosition(NativePoint, NativeSize, PopupWindowPositionFlags, NativeRectangle, NativeSize)</a> function positions the pop-up window horizontally and vertically.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum PopupWindowPositionFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration PopupWindowPositionFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As PopupWindowPositionFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class PopupWindowPositionFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type PopupWindowPositionFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.HorizontalCenterAlign">**HorizontalCenterAlign**</td><td>4</td><td>Centers pop-up window horizontally relative to the coordinate specified by the `anchorPoint->x` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.HorizontalLeftAlign">**HorizontalLeftAlign**</td><td>0</td><td>Positions the pop-up window so that its left edge is aligned with the coordinate specified by the `anchorPoint->x` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.HorizontalRightAlign">**HorizontalRightAlign**</td><td>8</td><td>Positions the pop-up window so that its right edge is aligned with the coordinate specified by the `anchorPoint->x` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.VerticalBottomAlign">**VerticalBottomAlign**</td><td>32</td><td>Positions the pop-up window so that its bottom edge is aligned with the coordinate specified by the `anchorPoint->y` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.VerticalTopAlign">**VerticalTopAlign**</td><td>0</td><td>Positions the pop-up window so that its top edge is aligned with the coordinate specified by the `anchorPoint->y` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.VerticalCenterAlign">**VerticalCenterAlign**</td><td>16</td><td>Centers the pop-up window vertically relative to the coordinate specified by the `anchorPoint->y` parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.Horizontal">**Horizontal**</td><td>0</td><td>If the pop-up window cannot be shown at the specified location without overlapping the excluded rectangle, the system tries to accommodate the requested horizontal alignment before the requested vertical alignment.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.Vertical">**Vertical**</td><td>64</td><td>If the pop-up window cannot be shown at the specified location without overlapping the excluded rectangle, the system tries to accommodate the requested vertical alignment before the requested horizontal alignment.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.PopupWindowPositionFlags.WorkArea">**WorkArea**</td><td>65536</td><td>Restricts the pop-up window to within the screen's work area. 

 If this flag is not set, the pop-up window is restricted to the work area only if the input point is within the work area.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd565861%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd565861%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />