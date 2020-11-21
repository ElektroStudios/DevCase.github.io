# ProcessInformation Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation_hProcess">hProcess</a></td><td>
A handle to the newly created process. The handle is used to specify the process in all functions that perform operations on the process object.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation_hThread">hThread</a></td><td>
A handle to the primary thread of the newly created process. The handle is used to specify the thread in all functions that perform operations on the thread object.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation_ProcessId">ProcessId</a></td><td>
A value that can be used to identify a process. The value is valid from the time the process is created until all handles to the process are closed and the process object is freed; at this point, the identifier may be reused.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation_ThreadId">ThreadId</a></td><td>
A value that can be used to identify a thread. The value is valid from the time the thread is created until all handles to the thread are closed and the thread object is freed; at this point, the identifier may be reused.</td></tr></table>&nbsp;
<a href="#processinformation-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessInformation">ProcessInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />