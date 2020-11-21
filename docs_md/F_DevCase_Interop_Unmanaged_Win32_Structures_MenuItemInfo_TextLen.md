# MenuItemInfo.TextLen Field
 

The length of the menu item text, in characters, when information is received about a menu item of the "<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Text</a> type. 

 However, TextLen is used only if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Type</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member and is zero otherwise. 

 Also, TextLen is ignored when the content of a menu item is set by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetMenuItemInfo">SetMenuItemInfo(IntPtr, UInt32, Boolean, MenuItemInfo)</a> function. 

 The TextLen member is used when the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Text</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int TextLen
```

**VB**<br />
``` VB
Public TextLen As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemInfo
Dim value As Integer

value = instance.TextLen

instance.TextLen = value
```

**C++**<br />
``` C++
public:
int TextLen
```

**F#**<br />
``` F#
val mutable TextLen: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">MenuItemInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />