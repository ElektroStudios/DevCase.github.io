# ProcessUtil.SetCurrentProcessPrivileges Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetCurrentProcessPrivileges">SetCurrentProcessPrivileges(ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the current process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IPC_Tools_ProcessUtil_SetCurrentProcessPrivileges_1">SetCurrentProcessPrivileges(String, ProcessPrivileges, PrivilegeStates)</a></td><td>
Enable or disable a process privilege for the current process. 

 Note that this method cannot add or remove privileges for external processes. It can only enable existing privileges that are currently disabled, or disable existing privileges that are currently enabled. 

 Trying to enable or disable a removed privilege will result in a exception. 

 In order to avoid this exception, it is recommended to call <a href="M_DevCase_Core_IPC_Tools_ProcessUtil_GetProcessPrivilegeState">GetProcessPrivilegeState(Process, ProcessPrivileges)</a> to determine whether a privilege is removed before calling this method.</td></tr></table>&nbsp;
<a href="#processutil.setcurrentprocessprivileges-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />