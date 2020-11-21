# ReparseDataBuffer Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a></td><td>
A buffer that contains the Unicode strings for the substitute name and the print name, as described by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameOffset">SubstituteNameOffset</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameOffset">PrintNameOffset</a>, and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameLength">PrintNameLength</a>. 

 The substitute name string MUST be a Unicode path to the target of the symbolic link. 

 The print name string MUST be a Unicode string, suitable for display to a user, that also identifies the target of the symbolic link.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Flags">Flags</a></td><td>
Flags that pecifies whether the substitute is an absolute target path name or a path name relative to the directory containing the symbolic link.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameLength">PrintNameLength</a></td><td>
The length, in bytes, of the print name string. 

 If there is a terminating null character at the end of the string, it is not included in the PrintNameLength count. 

 This value MUST be greater than or equal to 0.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_PrintNameOffset">PrintNameOffset</a></td><td>
The offset, in bytes, from the beginning of the PathBuffer field, at which the print name is located. 

 The print name is the user-friendly name the client MUST return to the application if it requests the name of the symbolic link target</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_ReparseDataLength">ReparseDataLength</a></td><td>
Size, in bytes, of the reparse data in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a> member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_ReparseTag">ReparseTag</a></td><td>
Reparse point tag. Must be a Microsoft reparse point tag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Reserved">Reserved</a></td><td>
Length, in bytes, of the unparsed portion of the file name pointed to by the FileName member of the associated file object. 

 This member is only valid for create operations when the I/O fails with STATUS_REPARSE. For all other purposes, such as setting or querying a reparse point for the reparse data, this member is treated as reserved.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a></td><td>
The length, in bytes, of the substitute name string. 

 If there is a terminating null character at the end of the string, it is not included in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameLength">SubstituteNameLength</a> count. 

 This value MUST be greater than or equal to 0.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_SubstituteNameOffset">SubstituteNameOffset</a></td><td>
The offset, in bytes, from the beginning of the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_Buffer">Buffer</a> member, at which the substitute name is located. 

 The substitute name is the name the client MUST use to access this file if it requires to follow the symbolic link.</td></tr></table>&nbsp;
<a href="#reparsedatabuffer-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer">ReparseDataBuffer Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />