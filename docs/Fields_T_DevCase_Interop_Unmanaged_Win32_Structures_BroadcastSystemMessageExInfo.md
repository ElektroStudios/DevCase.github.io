# BroadcastSystemMessageExInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo">BroadcastSystemMessageExInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hdesk">Hdesk</a></td><td>
A desktop handle to the window specified by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hwnd">Hwnd</a>. 

 This value is returned only if <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">ReturnHDesk</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hwnd">Hwnd</a></td><td>
A handle to the window that denied the request. 

 This value is returned only if <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Luid">Luid</a></td><td>
A locally unique identifier (LUID) for the window.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of BroadcastSystemMessageExInfo)` before calling any function.</td></tr></table>&nbsp;
<a href="#broadcastsystemmessageexinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo">BroadcastSystemMessageExInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />