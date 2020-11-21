# MenuItemMask Enumeration
 

Specifies a mask type for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> field.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MenuItemMask
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MenuItemMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemMask
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MenuItemMask
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MenuItemMask
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Bitmap">**Bitmap**</td><td>128</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpItem">BmpItem</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.CheckMarks">**CheckMarks**</td><td>8</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpChecked">BmpChecked</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpUnchecked">BmpUnchecked</a> members.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Data">**Data**</td><td>32</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_ItemData">ItemData</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Ftype">**Ftype**</td><td>256</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Type">Type</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Id">**Id**</td><td>2</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Id">Id</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.State">**State**</td><td>1</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_State">State</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Text">**Text**</td><td>64</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Submenu">**Submenu**</td><td>4</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_SubMenu">SubMenu</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemMask.Type">**Type**</td><td>16</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Type">Type</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a> members. 

Type is replaced by Bitmap, Ftype, and Text.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />