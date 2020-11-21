# NativeMethods.DeleteDC Method 
 


## Overload List
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteDC">DeleteDC(IntPtr)</a></td><td>
Deletes the specified device context (DC). 

 An application must not delete a DC whose handle was obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDC">GetDC(IntPtr)</a> function. instead, it must call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC(IntPtr, IntPtr)</a> function to free the DC.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteDC_1">DeleteDC(SafeHandle)</a></td><td>
Deletes the specified device context (DC). 

 An application must not delete a DC whose handle was obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDC">GetDC(IntPtr)</a> function. instead, it must call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ReleaseDC">ReleaseDC(IntPtr, IntPtr)</a> function to free the DC.</td></tr></table>&nbsp;
<a href="#nativemethods.deletedc-method">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />