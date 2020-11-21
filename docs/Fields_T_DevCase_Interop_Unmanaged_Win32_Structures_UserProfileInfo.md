# UserProfileInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo">UserProfileInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_DefaultPath">DefaultPath</a></td><td>
A pointer to the default user profile path. 

 This member can be a null reference (`Nothing` in Visual Basic).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_Flags">Flags</a></td><td>
Profle flags.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_PolicyPath">PolicyPath</a></td><td>
Not used, set it to a null reference (`Nothing` in Visual Basic).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_ProfilePath">ProfilePath</a></td><td>
A pointer to the roaming user profile path. 

 If the user does not have a roaming profile, this member can be a null reference (`Nothing` in Visual Basic). 

 To retrieve the user's roaming profile path, call the `NetUserGetInfo` function, specifying information level `3` or `4`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_RegistryHandle">RegistryHandle</a></td><td>
A handle To the `HKEY_CURRENT_USER` registry subtree.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_ServerName">ServerName</a></td><td>
A pointer To the name Of the validating domain controller, In `NetBIOS` format.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of UserProfileInfo)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo_UserName">UserName</a></td><td>
A pointer to the name of the user. 

 This member is used as the base name of the directory in which to store a new profile.</td></tr></table>&nbsp;
<a href="#userprofileinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_UserProfileInfo">UserProfileInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />