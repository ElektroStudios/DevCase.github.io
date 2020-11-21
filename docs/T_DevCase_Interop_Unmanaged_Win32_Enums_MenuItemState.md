# MenuItemState Enumeration
 

Specifies a menu item state.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MenuItemState
```

**VB**<br />
``` VB
Public Enumeration MenuItemState
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemState
```

**C++**<br />
``` C++
public enum class MenuItemState
```

**F#**<br />
``` F#
type MenuItemState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Enabled">**Enabled**</td><td>0</td><td>The menu item is present and can be selected. 

 This is the default state.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Grayed">**Grayed**</td><td>1</td><td>The menu item is present but greyed-out and cannot be selected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Disabled">**Disabled**</td><td>2</td><td>The menu item is present but can not be selected.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Removed">**Removed**</td><td>-1</td><td>The menu item is not present.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Checked">**Checked**</td><td>8</td><td>Places a check mark next to the menu item. 

 If the application provides check-mark bitmaps, this flag displays the check-mark bitmap next to the menu item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MenuItemState.Unchecked">**Unchecked**</td><td>0</td><td>Does not place a check mark next to the item (default). 

 If the application supplies check-mark bitmaps, this flag displays the clear bitmap next to the menu item.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647636%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647636%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />