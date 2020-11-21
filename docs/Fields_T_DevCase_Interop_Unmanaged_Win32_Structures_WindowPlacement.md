# WindowPlacement Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement">WindowPlacement</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_Flags">Flags</a></td><td>
Specifies flags that control the position of the minimized window and the method by which the window is restored.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_MaxPosition">MaxPosition</a></td><td>
The coordinates of the window's upper-left corner when the window is maximized.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_MinPosition">MinPosition</a></td><td>
The coordinates of the window's upper-left corner when the window is minimized.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_NormalPosition">NormalPosition</a></td><td>
The window's coordinates when the window is in the restored position.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of WindowPlacement)` before calling any function. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetWindowPlacement">GetWindowPlacement(IntPtr, WindowPlacement)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPlacement">SetWindowPlacement(IntPtr, WindowPlacement)</a> fail if this member is not set correctly.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement_WindowState">WindowState</a></td><td>
The current show state of the window.</td></tr></table>&nbsp;
<a href="#windowplacement-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_WindowPlacement">WindowPlacement Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />