# MenuItemType Enumeration
 

Specifies a menu-item type for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Type">Type</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MenuItemType
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MenuItemType
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemType
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MenuItemType
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MenuItemType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.Bitmap">**Bitmap**</td><td>4</td><td>Displays the menu item using a bitmap. 

 The low-order word of the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> member is the bitmap handle, and the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a> member is ignored. 

Bitmap is replaced by <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Bitmap</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpItem">BmpItem</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.RadioCheck">**RadioCheck**</td><td>512</td><td>Displays selected menu items using a radio-button mark instead of a check mark if the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpChecked">BmpChecked</a> member is Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.Separator">**Separator**</td><td>2048</td><td>Specifies that the menu item is a separator. 

 A menu item separator appears as a horizontal dividing line. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> and cch members are ignored. 

 This value is valid only in a drop-down menu, submenu, or shortcut menu.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.Text">**Text**</td><td>0</td><td>Displays the menu item using a text string. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> member is the pointer to a null-terminated string, and the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a> member is the length of the string. 

Text is replaced by <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Text</a>.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.RightJustify">**RightJustify**</td><td>16384</td><td>Right-justifies the menu item and any subsequent items. 

 This value is valid only if the menu item is in a menu bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.Rightorder">**Rightorder**</td><td>8192</td><td>Specifies that menus cascade right-to-left (the default is left-to-right). 

 This is used to support right-to-left languages, such as Arabic and Hebrew.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.MenuBarBreak">**MenuBarBreak**</td><td>32</td><td>Places the menu item on a new line (for a menu bar), or in a new column (for a drop-down menu, submenu, or shortcut menu). 

 For a drop-down menu, submenu, or shortcut menu, a vertical line separates the new column from the old.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.MenuBreak">**MenuBreak**</td><td>64</td><td>Places the menu item on a new line (for a menu bar), or in a new column (for a drop-down menu, submenu, or shortcut menu). 

 For a drop-down menu, submenu, or shortcut menu, the columns are not separated by a vertical line.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemType.OwnerDraw">**OwnerDraw**</td><td>256</td><td>Assigns responsibility for drawing the menu item to the window that owns the menu. 

 The window receives a `WM_MEASUREITEM` message before the menu is displayed for the first time, and a `WM_DRAWITEM` message whenever the appearance of the menu item must be updated. 

 If this value is specified, the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> member contains an application-defined value.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />