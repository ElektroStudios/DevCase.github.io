# MenuMask Enumeration
 

Specifies a mask type for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Mask">Mask</a> field. Indicate the members to be retrieved or set (except for ApplyToSubmenus).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum MenuMask
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration MenuMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuMask
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class MenuMask
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type MenuMask
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.ApplyToSubmenus">**ApplyToSubmenus**</td><td>-2147483648</td><td>Settings apply to the menu and all of its submenus. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetMenuItemInfo">SetMenuItemInfo(IntPtr, UInt32, Boolean, MenuItemInfo)</a> function uses this flag and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuItemInfo">GetMenuItemInfo(IntPtr, UInt32, Boolean, MenuItemInfo)</a> function ignores this flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.Background">**Background**</td><td>2</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_BrushBack">BrushBack</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.HelpId">**HelpId**</td><td>4</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_ContextHelpID">ContextHelpID</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.MaxHeight">**MaxHeight**</td><td>1</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Max">Max</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.MenuData">**MenuData**</td><td>8</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_MenuData">MenuData</a> member.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuMask.Style">**Style**</td><td>16</td><td>Retrieves or sets the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Style">Style</a> member.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647575%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647575%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />