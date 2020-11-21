# WindowHitTestRegions Enumeration
 

Specifies the position of the cursor hot spot. 

 Options available when a form is tested for mouse positions with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NchitTest</a> message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WindowHitTestRegions
```

**VB**<br />
``` VB
Public Enumeration WindowHitTestRegions
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowHitTestRegions
```

**C++**<br />
``` C++
public enum class WindowHitTestRegions
```

**F#**<br />
``` F#
type WindowHitTestRegions
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.Error">**Error**</td><td>-2</td><td>On the screen background or on a dividing line between windows. 

 Same as NoWhere, except that the `DefWindowProc` function produces a system beep to indicate an error.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.TransparentOrCovered">**TransparentOrCovered**</td><td>-1</td><td>In a window currently covered by another window in the same thread. 

 The message will be sent to underlying windows in the same thread until one of them returns a code that is not TransparentOrCovered.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.NoWhere">**NoWhere**</td><td>0</td><td>On the screen background or on a dividing line between windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.ClientArea">**ClientArea**</td><td>1</td><td>In a client area.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.TitleBar">**TitleBar**</td><td>2</td><td>In a title bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.SystemMenu">**SystemMenu**</td><td>3</td><td>In a window menu or in a Close button in a child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.GrowBox">**GrowBox**</td><td>4</td><td>In a grow box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.Menu">**Menu**</td><td>5</td><td>In a menu.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.HorizontalScrollBar">**HorizontalScrollBar**</td><td>6</td><td>In a horizontal scroll bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.VerticalScrollBar">**VerticalScrollBar**</td><td>7</td><td>In the vertical scroll bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.MinimizeButton">**MinimizeButton**</td><td>8</td><td>In a Minimize button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.MaximizeButton">**MaximizeButton**</td><td>9</td><td>In a Maximize button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.LeftSizeableBorder">**LeftSizeableBorder**</td><td>10</td><td>In the left border of a resizable window. 

 The user can click the mouse to resize the window horizontally.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.RightSizeableBorder">**RightSizeableBorder**</td><td>11</td><td>In the right border of a resizable window. 

 The user can click the mouse to resize the window horizontally.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.TopSizeableBorder">**TopSizeableBorder**</td><td>12</td><td>In the upper-horizontal border of a window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.TopLeftSizeableCorner">**TopLeftSizeableCorner**</td><td>13</td><td>In the upper-left corner of a window border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.TopRightSizeableCorner">**TopRightSizeableCorner**</td><td>14</td><td>In the upper-right corner of a window border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.BottomSizeableBorder">**BottomSizeableBorder**</td><td>15</td><td>In the lower-horizontal border of a resizable window. 

 The user can click the mouse to resize the window vertically.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.BottomLeftSizeableCorner">**BottomLeftSizeableCorner**</td><td>16</td><td>In the lower-left corner of a border of a resizable window. 

 The user can click the mouse to resize the window diagonally.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.BottomRightSizeableCorner">**BottomRightSizeableCorner**</td><td>17</td><td>In the lower-right corner of a border of a resizable window. 

 The user can click the mouse to resize the window diagonally.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.NonSizableBorder">**NonSizableBorder**</td><td>18</td><td>In the border of a window that does not have a sizing border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.CloseButton">**CloseButton**</td><td>20</td><td>In a Close button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowHitTestRegions.HelpButton">**HelpButton**</td><td>21</td><td>In a Help button.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms645618%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms645618%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />