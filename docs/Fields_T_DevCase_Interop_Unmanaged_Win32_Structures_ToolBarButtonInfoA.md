# ToolBarButtonInfoA Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA">ToolBarButtonInfoA</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_ButtonWidth">ButtonWidth</a></td><td>
Width of the button, in pixels.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_CommandId">CommandId</a></td><td>
Command identifier of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_ImageIndex">ImageIndex</a></td><td>
Image index of the button. 

 Set this member to `I_IMAGECALLBACK`, and the toolbar will send the `TBN_GETDISPINFO` notification code to retrieve the image index when it is needed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_lParam">lParam</a></td><td>
Application-defined value associated with the button</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Mask">Mask</a></td><td>
Set of flags that indicate which members contain valid information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ToolBarButtonInfoA)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_State">State</a></td><td>
State flags of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Style">Style</a></td><td>
Style flags of the button.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Text">Text</a></td><td>
Address of a character buffer that contains or receives the button text.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_TextSize">TextSize</a></td><td>
Size of the buffer at <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Text">Text</a> field. 

 If the button information is being set, this member is ignored.</td></tr></table>&nbsp;
<a href="#toolbarbuttoninfoa-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA">ToolBarButtonInfoA Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />