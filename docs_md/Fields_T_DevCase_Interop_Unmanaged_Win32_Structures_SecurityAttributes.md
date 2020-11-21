# SecurityAttributes Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_InheritHandle">InheritHandle</a></td><td>
A value that specifies whether the returned handle is inherited when a new process is created. 

 If this member is `true` (`True` in Visual Basic), the new process inherits the handle.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SecurityDescriptor">SecurityDescriptor</a></td><td>
A pointer to a `SECURITY_DESCRIPTOR` structure that controls access to the object. 

 If the value of this member is Zero, the object is assigned the default security descriptor associated with the access token of the calling process. 

 This is not the same as granting access to everyone by assigning a NULL discretionary access control list (DACL). 

 By default, the default DACL in the access token of a process allows access only to the user represented by the access token.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of SecurityAttributes)` before calling any function.</td></tr></table>&nbsp;
<a href="#securityattributes-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_SecurityAttributes">SecurityAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />