# TokenPrivileges Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges_PrivilegeCount">PrivilegeCount</a></td><td>
This must be set to the number of entries in the Privileges array</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges_Privileges">Privileges</a></td><td>
Specifies an array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_LuidAndAttributes">LuidAndAttributes</a> structures. 

 Each structure contains the LUID and attributes of a privilege. 

 To get the name of the privilege associated with a LUID, call the `LookupPrivilegeName` function, passing the address of the LUID as the value of the `lpLuid` parameter.</td></tr></table>&nbsp;
<a href="#tokenprivileges-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TokenPrivileges">TokenPrivileges Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />