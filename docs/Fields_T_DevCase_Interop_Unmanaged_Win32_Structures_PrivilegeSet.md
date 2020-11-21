# PrivilegeSet Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">PrivilegeSet</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Control">Control</a></td><td>
Specifies a control flag related to the privileges. 

 The `PRIVILEGE_SET_ALL_NECESSARY` control flag is currently defined. 

 It indicates that all of the specified privileges must be held by the process requesting access. 

 If this flag is not set, the presence of any privileges in the user's access token grants the access.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_PrivilegeCount">PrivilegeCount</a></td><td>
The number of privileges in the privilege set.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet_Privileges">Privileges</a></td><td>
Specifies an array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a> structures describing the set's privileges.</td></tr></table>&nbsp;
<a href="#privilegeset-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PrivilegeSet">PrivilegeSet Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />