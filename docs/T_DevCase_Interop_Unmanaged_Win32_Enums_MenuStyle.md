# MenuStyle Enumeration
 

Specifies a menu style for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Style">Style</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MenuStyle
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MenuStyle
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuStyle
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MenuStyle
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MenuStyle
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.AutoDismis">**AutoDismis**</td><td>268435456</td><td>Menu automatically ends when mouse is outside the menu for approximately 10 seconds..</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.CheckOrBmp">**CheckOrBmp**</td><td>67108864</td><td>The same space is reserved for the check mark and the bitmap. If the check mark is drawn, the bitmap is not. All checkmarks and bitmaps are aligned. Used for menus where some items use checkmarks and some use bitmaps.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.DragDrop">**DragDrop**</td><td>536870912</td><td>Menu items are OLE drop targets or drag sources. Menu owner receives "WM_MENUDRAG" and "WM_MENUGETOBJECT" messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.Modeless">**Modeless**</td><td>1073741824</td><td>Menu is modeless; that is, there is no menu modal message loop while the menu is active.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.NoCheck">**NoCheck**</td><td>-2147483648</td><td>No space is reserved to the left of an item for a check mark. The item can still be selected, but the check mark will not appear next to the item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuStyle.NotifyByPos">**NotifyByPos**</td><td>134217728</td><td>Menu owner receives a "WM_MENUCOMMAND" message, instead of a "WM_COMMAND" message, when the user makes a selection. "MenuStyle.NOTIFYBYPOS" is a menu header style and has no effect when applied to individual sub menus.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647575%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647575%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />