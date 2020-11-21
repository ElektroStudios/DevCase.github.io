# MenuInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo">MenuInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_BrushBack">BrushBack</a></td><td>
A handle to the brush to be used for the menu's background.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_ContextHelpID">ContextHelpID</a></td><td>
The context help identifier. 

 This is the same value used in the `GetMenuContextHelpId` and `SetMenuContextHelpId` functions.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Mask">Mask</a></td><td>
The members to be retrieved or set (except for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuMask">ApplyToSubmenus</a>). 

 This member can be one or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuMask">MenuMask</a> enumeration values.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Max">Max</a></td><td>
The maximum height of the menu in pixels. 

 When the menu items exceed the space available, scroll bars are automatically used. 

 The default (`0`) is the screen height.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_MenuData">MenuData</a></td><td>
An application-defined value.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of MenuInfo)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo_Style">Style</a></td><td>
The menu style.</td></tr></table>&nbsp;
<a href="#menuinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MenuInfo">MenuInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />