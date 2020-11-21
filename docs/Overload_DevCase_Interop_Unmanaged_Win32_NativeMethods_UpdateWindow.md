# NativeMethods.UpdateWindow Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateWindow">UpdateWindow(IntPtr)</a></td><td>
Updates the client area of the specified window by sending a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message to the window if the window's update region is not empty. 

 The function sends a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message directly to the window procedure of the specified window, bypassing the application queue. If the update region is empty, no message is sent.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateWindow_1">UpdateWindow(SafeHandle)</a></td><td>
Updates the client area of the specified window by sending a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message to the window if the window's update region is not empty. 

 The function sends a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message directly to the window procedure of the specified window, bypassing the application queue. If the update region is empty, no message is sent.</td></tr></table>&nbsp;
<a href="#nativemethods.updatewindow-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />