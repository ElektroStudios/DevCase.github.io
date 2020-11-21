# NotifyIconIdentifier Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier">NotifyIconIdentifier</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier_Guid">Guid</a></td><td>
A registered GUID that identifies the icon.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier_Hwnd">Hwnd</a></td><td>
A handle to the parent window used by the notification's callback function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier_Id">Id</a></td><td>
The application-defined identifier of the notification icon. 

 Multiple icons can be associated with a single `HWND`, each with their own Id.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of NotifyIconIdentifier)` before calling any function.</td></tr></table>&nbsp;
<a href="#notifyiconidentifier-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier">NotifyIconIdentifier Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />