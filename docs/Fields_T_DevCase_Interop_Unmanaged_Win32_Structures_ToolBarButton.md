# ToolBarButton Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton_BitmapIndex">BitmapIndex</a></td><td>
Zero-based index of the button image. 

 Set this member to `I_IMAGECALLBACK`, and the toolbar will send the `TBN_GETDISPINFO` notification code to retrieve the image index when it is needed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton_CommandId">CommandId</a></td><td>
Command identifier associated with the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton_Data">Data</a></td><td>
Application-defined value.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton_TextOrIndex">TextOrIndex</a></td><td>
Zero-based index of the button string, or a pointer to a string buffer that contains text for the button. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton_TextOrIndex">TextOrIndex</a> member can return either a string pointer or an index.</td></tr></table>&nbsp;
<a href="#toolbarbutton-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />