# VolumeUtil Class
 

Contains volume info.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Shell.Tools.VolumeUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class VolumeUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class VolumeUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As VolumeUtil
```

**C++**<br />
``` C++
public ref class VolumeUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VolumeUtil =  
    class
        inherit AestheticObject
    end
```

The VolumeUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_IsCompressed">IsCompressed</a></td><td>
Gets a value that determines whether the current volume is a compressed volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_IsCompressed_1">IsCompressed(String)</a></td><td>
Gets a value that determines whether the specified volume is a compressed volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_IsReadOnly">IsReadOnly</a></td><td>
Gets a value that determines whether the current volume is a read only volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_IsReadOnly_1">IsReadOnly(String)</a></td><td>
Gets a value that determines whether the specified volume is a read only volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_MaxComponentPathLength">MaxComponentPathLength</a></td><td>
Gets the maximum path length for a `Unicode` path component for the current volume. 

 The `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 This type of path is composed of "path components" separated by backslashes, for example: `C:\component1\component2`. 

 The maximum extended-length path is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> property, read the property description for further details. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_MaxComponentPathLength_1">MaxComponentPathLength(String)</a></td><td>
Gets the maximum path length for a `Unicode` path component for the specified volume. 

 The `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The maximum extended-length path is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> property, read the property description for further details. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SerialNumber">SerialNumber</a></td><td>
Gets the serial number, in Hexadecimal, that the operating system assigned to the current volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SerialNumber_1">SerialNumber(String)</a></td><td>
Gets the serial number, in Hexadecimal, that the operating system assigned to the specified volume.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsEncryption">SupportsEncryption</a></td><td>
Gets a value that determines whether the current volume supports `Encryption File System` (`EFS`).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsEncryption_1">SupportsEncryption(String)</a></td><td>
Gets a value that determines whether the specified volume supports `Encryption File System` (`EFS`).</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedFileAttributes">SupportsExtendedFileAttributes</a></td><td>
Gets a value that determines whether the current volume supports extended file attributes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedFileAttributes_1">SupportsExtendedFileAttributes(String)</a></td><td>
Gets a value that determines whether the specified volume supports extended file attributes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedPath">SupportsExtendedPath</a></td><td>
Gets a value that determines whether the current volume supports usage of Unicode extended-length paths. 

 Read the property description of <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> and <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> properties for further details.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsExtendedPath_1">SupportsExtendedPath(String)</a></td><td>
Gets a value that determines whether the specified volume supports usage of Unicode extended-length paths. 

 Read the property description of <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a> and <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> properties for further details.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsFileCompression">SupportsFileCompression</a></td><td>
Gets a value that determines whether the current volume supports file-based compression.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsFileCompression_1">SupportsFileCompression(String)</a></td><td>
Gets a value that determines whether the specified volume supports file-based compression.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsHardLinks">SupportsHardLinks</a></td><td>
Gets a value that determines whether the current volume supports hard links.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")</td><td><a href="P_DevCase_Core_Shell_Tools_VolumeUtil_SupportsHardLinks_1">SupportsHardLinks(String)</a></td><td>
Gets a value that determines whether the specified volume supports hard links.</td></tr></table>&nbsp;
<a href="#volumeutil-class">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 To specify an extended-length path, you must use the "`\\?\`" prefix when calling a `Windows API` function, for example: "`\\?\C:\very long path`".</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedUncPathPrefix">ExtendedUncPathPrefix</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 The extended-length path prefix can also be used with paths constructed according to the universal naming convention (`UNC`). To specify such a path using `UNC`, you must use the "`\\?\UNC\`" prefix, for example: "`\\?\UNC\server\Very long path`".</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxExtendedPathLength">MaxExtendedPathLength</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters, however, the `Windows API` has many functions that also have `Unicode` versions to permit an extended-length path for a maximum total path length of approximately `32.767` characters. 

 The extended-length path prefix is defined in the <a href="F_DevCase_Core_Shell_Tools_VolumeUtil_ExtendedPathPrefix">ExtendedPathPrefix</a> property, read the property description for further details about its usage. 

 Note that the maximum path of `32.767` characters is approximate, because the extended-length path prefix may be expanded to a longer string by the system at run time, and this expansion applies to the total length.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")![Static member](media/static.gif "Static member")</td><td><a href="F_DevCase_Core_Shell_Tools_VolumeUtil_MaxPathLength">MaxPathLength</a></td><td>
In `Windows` system, the maximum length for a path is composed of `260` characters. 

 A local path is structured in the following order: drive letter, colon, backslash, name components separated by backslashes, and a terminating null character. 

 For example, the maximum path on drive `C:\` is "`C:\some 256-character path string{NUL}`" where "`{NUL}`" represents the invisible terminating null character for the current system codepage.</td></tr></table>&nbsp;
<a href="#volumeutil-class">Back to Top</a>

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
<a href="#volumeutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />