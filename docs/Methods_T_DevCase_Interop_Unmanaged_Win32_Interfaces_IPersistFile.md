# IPersistFile Methods
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_GetClassID">GetClassID</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_GetCurFile">GetCurFile</a></td><td>
Retrieves the current name of the file associated with the object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_IsDirty">IsDirty</a></td><td>
Determines whether an object has changed since it was last saved to its current file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Load">Load</a></td><td>
Opens the specified file and initializes an object from the file contents.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Save">Save</a></td><td>
Saves a copy of the object to the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_SaveCompleted">SaveCompleted</a></td><td>
Notifies the object that it can write to its file. 

 It does this by notifying the object that it can revert from `NoScribble` mode (in which it must not write to its file), to `Normal` mode (in which it can). 

 The component enters `NoScribble` mode when it receives an <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile_Save">Save(String, Boolean)</a> call.</td></tr></table>&nbsp;
<a href="#ipersistfile-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersistFile">IPersistFile Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />