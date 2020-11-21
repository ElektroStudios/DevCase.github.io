# ObjectAttributes Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_Attributes">Attributes</a></td><td>
Flags that specifies object handle attributes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a></td><td>
Optional handle to the root object directory for the path name specified by the ObjectName member. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> is Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> must point to a fully qualified object name that includes the full path to the target object. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> is not Zero, <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_ObjectName">ObjectName</a> specifies an object name relative to the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> directory. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_RootDirectory">RootDirectory</a> handle can refer to a file system directory or an object directory in the object manager namespace.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SecurityDescriptor">SecurityDescriptor</a></td><td>
Specifies a security descriptor for the object when the object is created. 

 If this member is Zero, the object will receive default security settings.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SecurityQualityOfService">SecurityQualityOfService</a></td><td>
Optional quality of service to be applied to the object when it is created. Used to indicate the security impersonation level and context tracking mode (dynamic or static). 

 Currently, the InitializeObjectAttributes macro sets this member to Zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of ObjectAttributes)` before calling any function. 

 The InitializeObjectAttributes macro sets this member to `Marshal.SizeOf(Of ObjectAttributes)`.</td></tr></table>&nbsp;
<a href="#objectattributes-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />