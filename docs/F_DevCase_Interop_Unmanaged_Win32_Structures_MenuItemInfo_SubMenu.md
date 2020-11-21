# MenuItemInfo.SubMenu Field
 

A handle to the drop-down menu or submenu associated with the menu item. 

 If the menu item is not an item that opens a drop-down menu or submenu, this member is Zero. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Submenu</a> to use SubMenu.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr SubMenu
```

**VB**<br />
``` VB
Public SubMenu As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemInfo
Dim value As IntPtr

value = instance.SubMenu

instance.SubMenu = value
```

**C++**<br />
``` C++
public:
IntPtr SubMenu
```

**F#**<br />
``` F#
val mutable SubMenu: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">MenuItemInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />