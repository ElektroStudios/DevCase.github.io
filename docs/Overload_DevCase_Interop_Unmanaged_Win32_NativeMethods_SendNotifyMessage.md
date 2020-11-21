# NativeMethods.SendNotifyMessage Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a></td><td>
Sends the specified message to a window or windows. 

 If the window was created by the calling thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> calls the window procedure for the window and does not return until the window procedure has processed the message. 

 If the window was created by a different thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> passes the message to the window procedure and returns immediately; it does not wait for the window procedure to finish processing the message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage_1">SendNotifyMessage(IntPtr, UInt32, IntPtr, IntPtr)</a></td><td>
Sends the specified message to a window or windows. 

 If the window was created by the calling thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> calls the window procedure for the window and does not return until the window procedure has processed the message. 

 If the window was created by a different thread, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SendNotifyMessage">SendNotifyMessage(IntPtr, WindowMessages, IntPtr, IntPtr)</a> passes the message to the window procedure and returns immediately; it does not wait for the window procedure to finish processing the message.</td></tr></table>&nbsp;
<a href="#nativemethods.sendnotifymessage-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />