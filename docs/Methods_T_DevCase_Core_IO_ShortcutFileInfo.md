# ShortcutFileInfo Methods
 

The <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_CopyTo">CopyTo</a></td><td>
Copies an existing shortcut file to a new file, allowing the overwriting of an existing file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Create">Create</a></td><td>
Creates the shortcut file. It overwrites any existing file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Decrypt">Decrypt</a></td><td>
Decrypts a shortcut file that was encrypted by the current account using the <a href="M_DevCase_Core_IO_ShortcutFileInfo_Encrypt">Encrypt()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Delete">Delete</a></td><td>
Deletes the shortcut file.
 (Overrides FileSystemInfo.Delete().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Encrypt">Encrypt</a></td><td>
Encrypts a shortcut file so that only the account used to encrypt the file can decrypt it.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Equals">Equals</a></td><td>
Determines whether the specified <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> is equal to this <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a>.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl">GetAccessControl()</a></td><td>
Gets a FileSecurity object that encapsulates the access control list (ACL) entries for the file described by the current <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl_1">GetAccessControl(AccessControlSections)</a></td><td>
Gets a FileSecurity object that encapsulates the specified type of access control list (ACL) entries for the file described by the current <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_MoveTo">MoveTo</a></td><td>
Moves the shortcut file to a new location, providing the option to specify a new file name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open">Open(FileMode)</a></td><td>
Opens the shortcut file in the specified mode.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open_1">Open(FileMode, FileAccess)</a></td><td>
Opens the shortcut file in the specified mode with read, write, or read/write access.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Open_2">Open(FileMode, FileAccess, FileShare)</a></td><td>
Opens the shortcut file in the specified mode with read, write, or read/write access and the specified sharing option.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_OpenRead">OpenRead</a></td><td>
Creates a read-only FileStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_OpenWrite">OpenWrite</a></td><td>
Creates a write-only FileStream.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Refresh">Refresh</a></td><td>
Refreshes the state of the object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_Resolve">Resolve</a></td><td>
Resolves the target of a shortcut. 

 This is useful when the target of a shortcut file is changed from a drive letter to another, for example. 

 If the target can't be resolved, an error message would be displayed.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_ShortcutFileInfo_ToString">ToString</a></td><td>
Returns the shortcut' path as a string.
 (Overrides Object.ToString().)</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-methods">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_FileSystemInfo_FileSystemInfoExtensions_GetFileHandle">GetFileHandle</a></td><td>
Gets a file handle for the specified file or directory.
 (Defined by <a href="T_DevCase_Core_Extensions_FileSystemInfo_FileSystemInfoExtensions">FileSystemInfoExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#shortcutfileinfo-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />