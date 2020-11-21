# DirectoryInfoExtensions Class
 

Contains custom extension methods to use with DirectoryInfo type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.DirectoryInfo.DirectoryInfoExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assemblies:**&nbsp;&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)<br />&nbsp;&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)<br />

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class DirectoryInfoExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class DirectoryInfoExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As DirectoryInfoExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class DirectoryInfoExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type DirectoryInfoExtensions =  class end
```

The DirectoryInfoExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CopyTo">CopyTo(DirectoryInfo, DirectoryInfo)</a></td><td>
Coppies the source directory to the specified directory. 

 If the target directory already exists, an IOException is thrown.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CopyTo_1">CopyTo(DirectoryInfo, String)</a></td><td>
Coppies the source directory to the specified directory. 

 If the target directory already exists, an IOException is thrown.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateAllDirectories">CreateAllDirectories(DirectoryInfo)</a></td><td>
Creates all directories and subdirectories in the path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateAllDirectories_1">CreateAllDirectories(DirectoryInfo, DirectorySecurity)</a></td><td>
Creates all directories and subdirectories in the path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile">CreateZipFile(DirectoryInfo)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the source folder name to create the zip file, with Optimal compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_1">CreateZipFile(DirectoryInfo, CompressionLevel)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the source folder name to create the zip file, with the specified compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_3">CreateZipFile(DirectoryInfo, FileInfo)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with Optimal compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_6">CreateZipFile(DirectoryInfo, String)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with Optimal compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_2">CreateZipFile(DirectoryInfo, CompressionLevel, Encoding)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the source folder name to create the zip file, with the specified compression level and character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_4">CreateZipFile(DirectoryInfo, FileInfo, CompressionLevel)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with the specified compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_7">CreateZipFile(DirectoryInfo, String, CompressionLevel)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with the specified compression level and UTF8 character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_5">CreateZipFile(DirectoryInfo, FileInfo, CompressionLevel, Encoding)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with the specified compression level and character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_CreateZipFile_8">CreateZipFile(DirectoryInfo, String, CompressionLevel, Encoding)</a></td><td>
Creates a zip archive that contains the files and directories from the specified directory, using the specified filepath to create the zip file, with the specified compression level and character encoding for entry name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_ExtractIcon">ExtractIcon</a></td><td>
Extracts the icon associated for the source directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_GetSize">GetSize</a></td><td>
Gets the size of the directory, in bytes.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_HasParent">HasParent</a></td><td>
Determines whether the directory has a parent directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_HasRights">HasRights</a></td><td>
Determines whether the source directory contains the specified user-rights.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_MoveTo">MoveTo</a></td><td>
Moves the source directory to the specified directory. 

 If the target directory already exists, an IOException is thrown.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_OpenInExplorer">OpenInExplorer</a></td><td>
Opens the source directory in Explorer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_Recycle">Recycle</a></td><td>
Sends the source directory to the Recycle Bin.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_Rename">Rename</a></td><td>
Renames the name of the directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_SetRights">SetRights</a></td><td>
Sets the user-rights of the source directory.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions_ToShellFolder">ToShellFolder</a></td><td>
Converts the specified DirectoryInfo to ShellFolder.</td></tr></table>&nbsp;
<a href="#directoryinfoextensions-class">Back to Top</a>

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
<a href="#directoryinfoextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />