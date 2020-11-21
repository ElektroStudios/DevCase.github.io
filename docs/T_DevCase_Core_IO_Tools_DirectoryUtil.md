# DirectoryUtil Class
 

Contains directory related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.Tools.DirectoryUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DirectoryUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DirectoryUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DirectoryUtil
```

**C++**<br />
``` C++
public ref class DirectoryUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DirectoryUtil =  
    class
        inherit AestheticObject
    end
```

The DirectoryUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_AddAttributes">AddAttributes</a></td><td>
Adds directory-attribute(s) to the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink">CreateSymbolicLink(DirectoryInfo, DirectoryInfo)</a></td><td>
Creates a symbolic link of the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink_1">CreateSymbolicLink(DirectoryInfo, String)</a></td><td>
Creates a symbolic link of the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink_2">CreateSymbolicLink(String, DirectoryInfo)</a></td><td>
Creates a symbolic link of the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_CreateSymbolicLink_3">CreateSymbolicLink(String, String)</a></td><td>
Creates a symbolic link of the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetDirPaths">GetDirPaths(DirectoryInfo, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)</a></td><td>
Gets the filepaths those matches the criteria inside the specified directory and/or sub-DirectoryUtil.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetDirPaths_1">GetDirPaths(String, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)</a></td><td>
Gets the filepaths those matches the criteria inside the specified directory and/or sub-DirectoryUtil.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetDirs">GetDirs(DirectoryInfo, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)</a></td><td>
Gets the directories those matches the criteria inside the specified directory and/or sub-DirectoryUtil.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetDirs_1">GetDirs(String, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)</a></td><td>
Gets the directories those matches the criteria inside the specified directory and/or sub-DirectoryUtil.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetSize">GetSize</a></td><td>
Gets the size of a directory, in bytes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetSymbolicLinkTarget">GetSymbolicLinkTarget(DirectoryInfo)</a></td><td>
Gets the target of the specified symbolic link.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_GetSymbolicLinkTarget_1">GetSymbolicLinkTarget(String)</a></td><td>
Gets the target of the specified symbolic link.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_HasAttributes">HasAttributes</a></td><td>
Gets a value indicating whether a directory contains the specified directory-attribute(s).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_HasRights">HasRights(DirectoryInfo, FileSystemRights, AccessControlType)</a></td><td>
Determines whether a directory contains the specified user-rights.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_HasRights_1">HasRights(String, FileSystemRights, AccessControlType)</a></td><td>
Determines whether a directory contains the specified user-rights.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_IsDirectory">IsDirectory</a></td><td>
Determines whether the specified path points to a existing directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_IsMountPoint">IsMountPoint(DirectoryInfo)</a></td><td>
Determines whether whether the specified directory is a mount point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_IsMountPoint_1">IsMountPoint(String)</a></td><td>
Determines whether whether the specified directory is a mount point.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_IsSymbolicLink">IsSymbolicLink(DirectoryInfo)</a></td><td>
Determines whether whether the specified directory is a symbolic link.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_IsSymbolicLink_1">IsSymbolicLink(String)</a></td><td>
Determines whether whether the specified directory is a symbolic link.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_OpenInExplorer">OpenInExplorer(DirectoryInfo)</a></td><td>
Opens the specified directory in Explorer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_OpenInExplorer_1">OpenInExplorer(String)</a></td><td>
Opens the specified directory in Explorer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_RemoveAttributes">RemoveAttributes</a></td><td>
Removes directory-attribute(s) from the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_Rename">Rename</a></td><td>
Renames a directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_SetAttributes">SetAttributes</a></td><td>
Sets the file-attribute(s) of the specified directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_SetRights">SetRights(DirectoryInfo, FileSystemRights, AccessControlType)</a></td><td>
Sets the user-rights of a directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DirectoryUtil_SetRights_1">SetRights(String, FileSystemRights, AccessControlType)</a></td><td>
Sets the user-rights of a directory.</td></tr></table>&nbsp;
<a href="#directoryutil-class">Back to Top</a>

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
<a href="#directoryutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />