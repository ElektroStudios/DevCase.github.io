# NativeMethods.CreateProcess Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a></td><td>
Creates a new process and its primary thread. The new process runs in the security context of the calling process. 

 If the calling process is impersonating another user, the new process uses the token for the calling process, not the impersonation token. 

 To run the new process in the security context of the user represented by the impersonation token, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessAsUser">CreateProcessAsUser(IntPtr, String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess_1">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfoEx, ProcessInformation)</a></td><td>
Creates a new process and its primary thread. The new process runs in the security context of the calling process. 

 If the calling process is impersonating another user, the new process uses the token for the calling process, not the impersonation token. 

 To run the new process in the security context of the user represented by the impersonation token, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessAsUser">CreateProcessAsUser(IntPtr, String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcessWithLogon">CreateProcessWithLogon(String, String, String, ProcessLogonFlags, String, StringBuilder, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> function.</td></tr></table>&nbsp;
<a href="#nativemethods.createprocess-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />