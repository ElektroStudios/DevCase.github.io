# FileInfoExtensions Methods
 

The <a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions</a> type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_ContainsFilename">ContainsFilename</a></td><td>
Determines whether the source IEnumerable(T) contains an element with the specified file name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CopyTo">CopyTo(FileInfo, DirectoryInfo)</a></td><td>
Copies the source file to the specified directory. 

 If the target file already exists, an IOException is thrown.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CopyTo_1">CopyTo(FileInfo, DirectoryInfo, Boolean)</a></td><td>
Copies the source file to the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateAllDirectories">CreateAllDirectories(FileInfo)</a></td><td>
Creates all directories and subdirectories in the path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateAllDirectories_1">CreateAllDirectories(FileInfo, DirectorySecurity)</a></td><td>
Creates all directories and subdirectories in the path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile">CreateZipFile(FileInfo)</a></td><td>
Creates a zip archive from the specified file, using the source filename to create the zip file, with Optimal compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile_1">CreateZipFile(FileInfo, CompressionLevel)</a></td><td>
Creates a zip archive from the specified file, using the source filename to create the zip file, with the specified compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile_2">CreateZipFile(FileInfo, FileInfo)</a></td><td>
Creates a zip archive from the specified file, using the specified filepath to create the zip file, with Optimal compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile_4">CreateZipFile(FileInfo, String)</a></td><td>
Creates a zip archive from the specified file, using the specified filepath to create the zip file, with Optimal compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile_3">CreateZipFile(FileInfo, FileInfo, CompressionLevel)</a></td><td>
Creates a zip archive from the specified file, using the specified filepath to create the zip file, with the specified compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_CreateZipFile_5">CreateZipFile(FileInfo, String, CompressionLevel)</a></td><td>
Creates a zip archive from the specified file, using the specified filepath to create the zip file, with the specified compression level.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_ExtractIcon">ExtractIcon</a></td><td>
Extracts the icon associated for the source file. 

 Note: the maximum size of the returned icon only can be 32x32.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_GetNameWithoutExtension">GetNameWithoutExtension</a></td><td>
Gets the name of the file, without the extension.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_HasExtension">HasExtension</a></td><td>
Determines whether the path includes a file extension.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_HasRights">HasRights</a></td><td>
Determines whether the source file contains the specified user-rights.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_IsAccesible">IsAccesible</a></td><td>
Determines whether the source file is accesible in the context of reading or writting to the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Lock">Lock(FileInfo)</a></td><td>
Locks read/write access to the specified file for other applications (during the lifetime of the current application). 

 To unlock the file, just dispose the returned FileStream object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Lock_1">Lock(FileInfo, FileShare)</a></td><td>
Locks read/write access to the specified file for other applications (during the lifetime of the current application). 

 To unlock the file, just dispose the returned FileStream object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_MoveTo">MoveTo(FileInfo, DirectoryInfo)</a></td><td>
Moves the source file to the specified directory. 

 If the target file already exists, an IOException is thrown.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_MoveTo_1">MoveTo(FileInfo, DirectoryInfo, Boolean)</a></td><td>
Moves the source file to the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OpenInExplorer">OpenInExplorer</a></td><td>
Opens the specified file in Explorer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OrderByCreationTime">OrderByCreationTime</a></td><td>
Sorts the elements of the source IEnumerable(T) by their CreationTime property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OrderByFileName">OrderByFileName</a></td><td>
Sorts the elements of the source IEnumerable(T) by their Name property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OrderByFileSize">OrderByFileSize</a></td><td>
Sorts the elements of the source IEnumerable(T) by their Length property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OrderByLastAccessTime">OrderByLastAccessTime</a></td><td>
Sorts the elements of the source IEnumerable(T) by their LastAccessTime property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_OrderByLastWriteTime">OrderByLastWriteTime</a></td><td>
Sorts the elements of the source IEnumerable(T) by their LastWriteTime property.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Recycle">Recycle</a></td><td>
Sends the source file to the Recycle Bin.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Rename">Rename(FileInfo, String)</a></td><td>
Renames the name of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_Rename_1">Rename(FileInfo, String, String)</a></td><td>
Renames the name of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_RenameExtension">RenameExtension</a></td><td>
Changes the extension of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_SetRights">SetRights</a></td><td>
Sets the user-rights of the source file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_FileInfo_FileInfoExtensions_ToShellFile">ToShellFile</a></td><td>
Converts the specified FileInfo to ShellFile.</td></tr></table>&nbsp;
<a href="#fileinfoextensions-methods">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#fileinfoextensions-methods">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />