# Win32FindDataW Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_AlternateFileName">AlternateFileName</a></td><td>
An alternative name for the file. This name is in the classic 8.3 file name format.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_CreationTime">CreationTime</a></td><td>
A FILETIME structure that specifies when a file or directory was created. If the underlying file system does not support creation time, this member is zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileAttributes">FileAttributes</a></td><td>
The FILE_ATTRIBUTE_SPARSE_FILE attribute on the file is set if any of the streams of the file have ever been sparse.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileName">FileName</a></td><td>
The name of the file.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileSizeHigh">FileSizeHigh</a></td><td>
The high-order DWORD value of the file size, in bytes. 

 This value is zero unless the file size is greater than MAXDWORD. 

 The size of the file is equal to (FileSizeHigh * (MAXDWORD+1)) + FileSizeLow.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileSizeLow">FileSizeLow</a></td><td>
The low-order DWORD value of the file size, in bytes.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_LastAccessTime">LastAccessTime</a></td><td>
A FILETIME structure. 

 For a file, the structure specifies when the file was last read from, written to, or for executable files, run. 

 For a directory, the structure specifies when the directory is created. 

 If the underlying file system does not support last access time, this member is zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_LastWriteTime">LastWriteTime</a></td><td>
A FILETIME structure. 

 For a file, the structure specifies when the file was last written to, truncated, or overwritten, for example, when WriteFile or SetEndOfFile are used. 

 The date and time are not updated when file attributes or security descriptors are changed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_Reserved0">Reserved0</a></td><td>
If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_FileAttributes">FileAttributes</a> member includes the FILE_ATTRIBUTE_REPARSE_POINT attribute, this member specifies the reparse point tag. Otherwise, this value is undefined and should not be used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW_Reserved1">Reserved1</a></td><td>
Reserved for future use.</td></tr></table>&nbsp;
<a href="#win32finddataw-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_Win32FindDataW">Win32FindDataW Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />