# ShellFileInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">ShellFileInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_Attributes">Attributes</a></td><td>
An array of values that indicates the attributes of the file object.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_DisplayName">DisplayName</a></td><td>
A string that contains the name of the file as it appears in the Windows Shell, or the path and file name of the file that contains the icon representing the file.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconHandle">IconHandle</a></td><td>
A handle to the icon that represents the file. 

 You are responsible for destroying this handle with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyIcon">DestroyIcon(IntPtr)</a> when you no longer need it.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_IconIndex">IconIndex</a></td><td>
The index of the icon image within the system image list.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo_TypeName">TypeName</a></td><td>
A string that describes the type of file.</td></tr></table>&nbsp;
<a href="#shellfileinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">ShellFileInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />