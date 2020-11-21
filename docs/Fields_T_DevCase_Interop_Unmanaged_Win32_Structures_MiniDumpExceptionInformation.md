# MiniDumpExceptionInformation Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">MiniDumpExceptionInformation</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation_ClientPointers">ClientPointers</a></td><td>
Determines where to get the memory regions pointed to by the ExceptionPointers member. Set to `true` (`True` in Visual Basic) if the memory resides in the process being debugged (the target process of the debugger). Otherwise, set to `false` (`False` in Visual Basic) if the memory resides in the address space of the calling program (the debugger process). 

 If you are accessing local memory (in the calling process) you should not set this member to `true` (`True` in Visual Basic).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation_ExceptionPointers">ExceptionPointers</a></td><td>
A pointer to an `EXCEPTION_POINTERS` structure ( GetExceptionPointers() ) specifying a computer-independent description of the exception and the processor context at the time of the exception.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation_ThreadId">ThreadId</a></td><td>
The identifier of the thread throwing the exception.</td></tr></table>&nbsp;
<a href="#minidumpexceptioninformation-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MiniDumpExceptionInformation">MiniDumpExceptionInformation Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />