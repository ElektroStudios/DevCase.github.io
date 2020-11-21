# AppbarData Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">AppbarData</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_CallbackMessage">CallbackMessage</a></td><td>
An application-defined message identifier. 

 The application uses the specified identifier for notification messages that it sends to the appbar identified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Hwnd">Hwnd</a> member. 

 This member is used when sending the `ABM_NEW` message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Edge">Edge</a></td><td>
A value that specifies an edge of the screen.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Hwnd">Hwnd</a></td><td>
The handle to the appbar window.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_LParam">LParam</a></td><td>
A message-dependent value.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_Rect">Rect</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure whose use varies depending on the message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of AppbarData)` before calling any function.</td></tr></table>&nbsp;
<a href="#appbardata-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">AppbarData Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />