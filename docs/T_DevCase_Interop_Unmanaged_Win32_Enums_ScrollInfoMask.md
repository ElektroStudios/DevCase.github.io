# ScrollInfoMask Enumeration
 

For <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Mask">Mask</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ScrollInfoMask
```

**VB**<br />
``` VB
Public Enumeration ScrollInfoMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As ScrollInfoMask
```

**C++**<br />
``` C++
public enum class ScrollInfoMask
```

**F#**<br />
``` F#
type ScrollInfoMask
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.Range">**Range**</td><td>1</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Min">Min</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Max">Max</a> members contain the minimum and maximum values for the scrolling range.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.Page">**Page**</td><td>2</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Page">Page</a> member contains the page size for a proportional scroll bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.Pos">**Pos**</td><td>4</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_Pos">Pos</a> member contains the scroll box position, which is not updated while the user drags the scroll box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.DisableNoScroll">**DisableNoScroll**</td><td>8</td><td>This value is used only when setting a scroll bar's parameters. 

 If the scroll bar's new parameters make the scroll bar unnecessary, disable the scroll bar instead of removing it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.TrackPos">**TrackPos**</td><td>16</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo_TrackPos">TrackPos</a> member contains the current position of the scroll box while the user is dragging it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ScrollInfoMask.All">**All**</td><td>23</td><td>Combination of Range, Page, Pos, and TrackPos.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb787537%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb787537%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />