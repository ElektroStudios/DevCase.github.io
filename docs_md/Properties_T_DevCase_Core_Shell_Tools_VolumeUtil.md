# VolumeUtil Properties
 


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
<a href="#volumeutil-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />