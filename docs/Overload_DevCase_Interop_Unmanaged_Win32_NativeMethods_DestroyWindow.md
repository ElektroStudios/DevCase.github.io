# NativeMethods.DestroyWindow Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a></td><td>
Destroys the specified window. The function sends <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Destroy</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcDestroy</a> messages to the window to deactivate it and remove the keyboard focus from it. 

 The function also destroys the window's menu, flushes the thread message queue, destroys timers, removes clipboard ownership, and breaks the clipboard viewer chain (if the window is at the top of the viewer chain). 

 If the specified window is a parent or owner window, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a> automatically destroys the associated child or owned windows when it destroys the parent or owner window. 

 The function first destroys child or owned windows, and then it destroys the parent or owner window. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a> also destroys modeless dialog boxes created by the `CreateDialog` function.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow_1">DestroyWindow(SafeHandle)</a></td><td>
Destroys the specified window. The function sends <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Destroy</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcDestroy</a> messages to the window to deactivate it and remove the keyboard focus from it. 

 The function also destroys the window's menu, flushes the thread message queue, destroys timers, removes clipboard ownership, and breaks the clipboard viewer chain (if the window is at the top of the viewer chain). 

 If the specified window is a parent or owner window, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a> automatically destroys the associated child or owned windows when it destroys the parent or owner window. 

 The function first destroys child or owned windows, and then it destroys the parent or owner window. 

<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DestroyWindow">DestroyWindow(IntPtr)</a> also destroys modeless dialog boxes created by the `CreateDialog` function.</td></tr></table>&nbsp;
<a href="#nativemethods.destroywindow-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />