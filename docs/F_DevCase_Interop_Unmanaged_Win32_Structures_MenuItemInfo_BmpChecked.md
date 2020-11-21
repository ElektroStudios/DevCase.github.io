# MenuItemInfo.BmpChecked Field
 

A handle to the bitmap to display next to the item if it is selected. 

 If this member is Zero, a default bitmap is used. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemType">RadioCheck</a> type value is specified, the default bitmap is a bullet, Otherwise it is a check mark. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">CheckMarks</a> to use BmpChecked.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr BmpChecked
```

**VB**<br />
``` VB
Public BmpChecked As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemInfo
Dim value As IntPtr

value = instance.BmpChecked

instance.BmpChecked = value
```

**C++**<br />
``` C++
public:
IntPtr BmpChecked
```

**F#**<br />
``` F#
val mutable BmpChecked: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo">MenuItemInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />