# FileTypeUtil Class
 

Contains file types related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.Tools.FileTypeUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class FileTypeUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class FileTypeUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileTypeUtil
```

**C++**<br />
``` C++
public ref class FileTypeUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type FileTypeUtil =  
    class
        inherit AestheticObject
    end
```

The FileTypeUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatch">GetFileTypeMatch(FileInfo, FileType)</a></td><td>
Determines whether a file type signature is match in the file header of the specified file, then returns a success percentage from `0%` to `100%` where `100%` means all the file signatures were found in the file header.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatch_1">GetFileTypeMatch(String, FileType)</a></td><td>
Determines whether a file type signature is match in the file header of the specified file, then returns a success percentage from `0%` to `100%` where `100%` means all the file signatures were found in the file header.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatches">GetFileTypeMatches(FileInfo)</a></td><td>
Tries to detect the file type of the specified file by analyzing a collection of known file type signatures on the file header, then returns a List(T) that contains the success percentage (0%...100%) of each file type found (if any).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatches_2">GetFileTypeMatches(String)</a></td><td>
Tries to detect the file type of the specified file by analyzing a collection of known file type signatures on the file header, then returns a List(T) that contains the success percentage (0%...100%) of each file type found (if any).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatches_1">GetFileTypeMatches(FileInfo, FileType[])</a></td><td>
Tries to detect the file type of the specified file by analyzing a collection of file type signatures on the file header, then returns a List(T) that contains the success percentage (0%...100%) of each file type found (if any).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_FileTypeUtil_GetFileTypeMatches_3">GetFileTypeMatches(String, FileType[])</a></td><td>
Tries to detect the file type of the specified file by analyzing a collection of file type signatures on the file header, then returns a List(T) that contains the success percentage (0%...100%) of each file type found (if any).</td></tr></table>&nbsp;
<a href="#filetypeutil-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_IO_Tools_FileTypeUtil_FiletypesDict">FiletypesDict</a></td><td>
A collection of known file types and its signatures. 

 The keys are the filetype extension, the values are an Array of file types which uses that extension.</td></tr></table>&nbsp;
<a href="#filetypeutil-class">Back to Top</a>

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
<a href="#filetypeutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />