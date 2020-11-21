# ChangeFilter Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">ChangeFilter</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter_ExtStatus">ExtStatus</a></td><td>
If the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function succeeds, this field contains information about the success.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ChangeFilter)`, otherwise the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</td></tr></table>&nbsp;
<a href="#changefilter-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter">ChangeFilter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />