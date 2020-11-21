# MenuItemInfo Structure
 

Contains information about a menu item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct MenuItemInfo
```

**VB**<br />
``` VB
Public Structure MenuItemInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As MenuItemInfo
```

**C++**<br />
``` C++
public value class MenuItemInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MenuItemInfo =  struct end
```

The MenuItemInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo__ctor">MenuItemInfo</a></td><td>
Initializes a new instance of the MenuItemInfo structure.</td></tr></table>&nbsp;
<a href="#menuiteminfo-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpChecked">BmpChecked</a></td><td>
A handle to the bitmap to display next to the item if it is selected. 

 If this member is Zero, a default bitmap is used. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemType">RadioCheck</a> type value is specified, the default bitmap is a bullet, Otherwise it is a check mark. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">CheckMarks</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpChecked">BmpChecked</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpItem">BmpItem</a></td><td>
A handle to the bitmap to be displayed. 

 It is used when the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Bitmap</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpUnchecked">BmpUnchecked</a></td><td>
A handle to the bitmap to display next to the item if it is not selected. 

 If this member is Zero, no bitmap is used. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">CheckMarks</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_BmpUnchecked">BmpUnchecked</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Id">Id</a></td><td>
An application-defined value that identifies the menu item. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Id</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Id">Id</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_ItemData">ItemData</a></td><td>
An application-defined value associated with the menu item. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Data</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_ItemData">ItemData</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a></td><td>
The members to be retrieved or set. 

 This member can be one or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuMask">MenuMask</a> Enum values.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of MenuItemInfo)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_State">State</a></td><td>
The menu item state. 

. Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">State</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_State">State</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_SubMenu">SubMenu</a></td><td>
A handle to the drop-down menu or submenu associated with the menu item. 

 If the menu item is not an item that opens a drop-down menu or submenu, this member is Zero. 

 Set <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Submenu</a> to use <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_SubMenu">SubMenu</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a></td><td>
The length of the menu item text, in characters, when information is received about a menu item of the "<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Text</a> type. 

 However, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a> is used only if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Type</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member and is zero otherwise. 

 Also, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a> is ignored when the content of a menu item is set by calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetMenuItemInfo">SetMenuItemInfo(IntPtr, UInt32, Boolean, MenuItemInfo)</a> function. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TextLen">TextLen</a> member is used when the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Text</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Type">Type</a></td><td>
The menu item type.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_TypeData">TypeData</a></td><td>
The contents of the menu item. 

 The meaning of this member depends on the value of fType, and is used only if the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuItemMask">Type</a> flag is set in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuItemInfo_Mask">Mask</a> member.</td></tr></table>&nbsp;
<a href="#menuiteminfo-structure">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#menuiteminfo-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647578%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />