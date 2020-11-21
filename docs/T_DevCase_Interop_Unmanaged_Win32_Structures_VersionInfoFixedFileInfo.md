# VersionInfoFixedFileInfo Structure
 

Contains version information for a file. This information is language and code page independent.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct VersionInfoFixedFileInfo
```

**VB**<br />
``` VB
Public Structure VersionInfoFixedFileInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As VersionInfoFixedFileInfo
```

**C++**<br />
``` C++
public value class VersionInfoFixedFileInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type VersionInfoFixedFileInfo =  struct end
```

The VersionInfoFixedFileInfo type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileDateLS">FileDateLS</a></td><td>
The least significant 32 bits of the file's 64-bit binary creation date and time stamp.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileDateMS">FileDateMS</a></td><td>
The most significant 32 bits of the file's 64-bit binary creation date and time stamp.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileFlags">FileFlags</a></td><td>
Contains a bitmask that specifies the Boolean attributes of the file.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileFlagsMask">FileFlagsMask</a></td><td>
Contains a bitmask that specifies the valid bits in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileFlags">FileFlags</a>. 

 A bit is valid only if it was defined when the file was created.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileOS">FileOS</a></td><td>
The operating system for which this file was designed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileSubtype">FileSubtype</a></td><td>
The function of the file. 

 The possible values depend on the value of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileType">FileType</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileType">FileType</a></td><td>
The general type of file.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileVersionLS">FileVersionLS</a></td><td>
The least significant 32 bits of the file's binary version number. 

 This member is used with dwFileVersionMS to form a 64-bit value used for numeric comparisons.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_FileVersionMS">FileVersionMS</a></td><td>
The most significant 32 bits of the file's binary version number. 

 This member is used with dwFileVersionLS to form a 64-bit value used for numeric comparisons.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_ProductVersionLS">ProductVersionLS</a></td><td>
The least significant 32 bits of the binary version number of the product with which this file was distributed. 

 This member is used with dwProductVersionMS to form a 64-bit value used for numeric comparisons.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_ProductVersionMS">ProductVersionMS</a></td><td>
The most significant 32 bits of the binary version number of the product with which this file was distributed. 

 This member is used with dwProductVersionLS to form a 64-bit value used for numeric comparisons.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_Signature">Signature</a></td><td>
Contains the value `0xFEEF04BD`. This is used with the szKey member of the `VS_VERSIONINFO` structure when searching a file for the VersionInfoFixedFileInfo structure.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_StrucVersion">StrucVersion</a></td><td>
The binary version number of this structure. 

 The high-order word of this member contains the major version number, and the low-order word contains the minor version number.</td></tr></table>&nbsp;
<a href="#versioninfofixedfileinfo-structure">Back to Top</a>

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
<a href="#versioninfofixedfileinfo-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680390(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680390(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />