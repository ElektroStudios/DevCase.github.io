# FlashWindowInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo">FlashWindowInfo</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_Count">Count</a></td><td>
The number of times to flash the window.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_Flags">Flags</a></td><td>
The flash status.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_Hwnd">Hwnd</a></td><td>
A handle to the window to be flashed. 

 The window can be either opened or minimized.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, in bytes. 

 Set this member to `Marshal.SizeOf(Of FlashWindowInfo)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_Timeout">Timeout</a></td><td>
The rate at which the window is to be flashed, in milliseconds. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo_Timeout">Timeout</a> is zero, the function uses the default cursor blink rate.</td></tr></table>&nbsp;
<a href="#flashwindowinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_FlashWindowInfo">FlashWindowInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />