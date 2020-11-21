# VersionInfoFixedFileInfo Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo">VersionInfoFixedFileInfo</a> type exposes the following members.


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
Contains the value `0xFEEF04BD`. This is used with the szKey member of the `VS_VERSIONINFO` structure when searching a file for the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo">VersionInfoFixedFileInfo</a> structure.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo_StrucVersion">StrucVersion</a></td><td>
The binary version number of this structure. 

 The high-order word of this member contains the major version number, and the low-order word contains the minor version number.</td></tr></table>&nbsp;
<a href="#versioninfofixedfileinfo-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_VersionInfoFixedFileInfo">VersionInfoFixedFileInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />